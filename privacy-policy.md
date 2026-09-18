# Privacy Policy

**Last updated: 18 September 2026**

## What this covers

This policy covers a private, single-operator tool that turns gameplay footage
recorded by its owner into short vertical videos and uploads them to the
owner's own YouTube channel.

The tool is not distributed, is not offered as a service, and has no users
other than its owner. It runs on one personal computer.

## Who operates it

David Knapp, operating the YouTube channel
[GTA 6 Viral Moments](https://www.youtube.com/channel/UCTyGxG-QYWMuPqSobydMxog).

Contact: ddresler20@gmail.com

## Use of YouTube API Services

This tool uses YouTube API Services to upload videos to its owner's own
channel and to read that channel's own statistics.

By using this tool, its operator is bound by the
[YouTube Terms of Service](https://www.youtube.com/t/terms).

Google's own handling of data is described in the
[Google Privacy Policy](https://policies.google.com/privacy).

Access granted to this tool can be revoked at any time through the
[Google security settings page](https://myaccount.google.com/permissions).

## What is accessed

The tool uses Google OAuth to obtain permission to act on the owner's own
YouTube channel. It requests three scopes:

| Scope | Why |
|---|---|
| `youtube.upload` | Upload videos to the owner's own channel |
| `youtube.readonly` | Check whether an upload finished processing |
| `yt-analytics.readonly` | Read view counts for the owner's own videos |

No data belonging to any other person or channel is accessed at any time.

## What is stored, and where

An OAuth refresh token is stored on the owner's own computer, in the Windows
Credential Manager, which encrypts it against the owner's user account. Where
that store is unavailable, the token is stored in an encrypted file whose key
is itself held in the credential store.

The tool also stores, locally on the same computer:

- video files recorded by the owner
- transcripts and detected events derived from those files
- titles, descriptions and tags generated for the owner's own videos
- view counts and retention figures for the owner's own published videos

All of this is held on one personal computer. None of it is transmitted to any
server operated by the author, because no such server exists.

## What is shared

Nothing is sold, rented, or shared for advertising or any other purpose.

Three third parties are involved in normal operation:

- **Google / YouTube** receives the videos being uploaded, along with their
  titles, descriptions and tags. Governed by the
  [Google Privacy Policy](https://policies.google.com/privacy).
- **Anthropic** receives short excerpts of transcript text and a small number
  of low-resolution frames, in order to judge which moments are worth
  publishing and to write titles. Governed by the
  [Anthropic Privacy Policy](https://www.anthropic.com/legal/privacy).
- **A text-to-speech provider**, only when the optional voiceover feature is
  enabled, receives one or two sentences of generated commentary.

No personal information about any third party is sent to any of them.

## Cookies and tracking

The tool has no web interface accessible to anyone else, sets no cookies, and
performs no tracking or analytics on any person.

## Data retention and deletion

Working files are deleted automatically after fourteen days.

The stored OAuth token is retained until the owner revokes it. It can be
deleted at any time by:

- revoking access at
  [myaccount.google.com/permissions](https://myaccount.google.com/permissions), or
- running the tool's own `youtube logout` command, which removes the stored
  token from the credential store.

Uploaded videos can be deleted at any time from YouTube Studio. Deleting a
video from YouTube removes it from YouTube entirely; any local copy is removed
by deleting it from the computer the tool runs on.

## Children

The tool is operated by an adult and is not directed at children. Videos it
uploads are marked as not made for kids.

## Changes to this policy

Any change will be published at this same address, with the date at the top
updated.

## Contact

Questions about this policy: ddresler20@gmail.com
