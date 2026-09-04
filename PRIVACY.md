# Privacy Policy — Avalon Church Sermon Publisher

_Last updated: September 4, 2026_

## What this is

The Avalon Church Sermon Publisher is an internal, automated tool operated by
Avalon Church. Each week it publishes the church's own sermon recording to the
Avalon Church podcast and to the Avalon Church YouTube channel. It has no
public users, no website, and no app. It runs unattended as a scheduled job,
and church volunteers interact with it only by filling out a Google Form and
saving files into a church-owned Google Drive folder.

## Who uses it

Only Avalon Church. The only Google account that authorizes this tool is the
account that manages the Avalon Church YouTube channel. No one outside the
church can sign in to it or use it.

## What Google data it accesses

**YouTube Data API.** Acting as the Avalon Church channel, the tool uploads
sermon videos, sets their titles, descriptions, and thumbnails, creates and
manages playlists for sermon series, and reads the channel's own list of
uploads to find the week's video. It does not access any other channel, and
it does not access information about viewers, subscribers, or commenters.

**Google Drive API.** Through a service account, the tool reads sermon audio,
video, artwork, and metadata files from one church-owned Drive folder and
moves them into a "Published" subfolder once they have been published.

**Google Forms.** Church volunteers submit each sermon's title, speaker,
series name, summary, scripture references, and optional series artwork.
The form does not collect respondents' email addresses.

## What it stores

- Sermon metadata (title, speaker, series, summary, scriptures) in the
  church's own Google Drive, as part of the church's records.
- The YouTube video ID and podcast episode ID of each published sermon.
- One OAuth refresh token for the channel account, kept as an encrypted
  secret in the church's GitHub repository.

It stores no data about viewers, listeners, subscribers, or the public. It
does not use any data for advertising and does not sell or rent any data.

## What it shares

For each sermon, the title, description, series artwork, and the link to the
YouTube video are sent to Transistor.fm, the church's podcast host, to create
the podcast episode. Series artwork is published in this public repository so
podcast apps can display it. Nothing else is shared with anyone.

## YouTube API Services

This tool uses YouTube API Services. By authorizing it, the channel account
agrees to the [YouTube Terms of Service](https://www.youtube.com/t/terms).
Google's handling of data is described in the
[Google Privacy Policy](https://policies.google.com/privacy). The channel
account can revoke this tool's access at any time from the
[Google account permissions page](https://myaccount.google.com/permissions).
Revoking access stops the tool immediately; nothing further is collected.

This tool's use of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## Retention

The OAuth token is kept until access is revoked or the tool is retired.
Sermon metadata, video IDs, and episode IDs are kept as part of the church's
records of its published sermons.

## Changes and contact

If this tool changes in a way that affects this policy, this page will be
updated. Questions about it can be sent to Avalon Church at
**info@avalonchurch.org**.
