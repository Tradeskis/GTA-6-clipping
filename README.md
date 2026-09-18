# GTA 6 Clipping

A private tool that turns gameplay footage recorded by its owner into short
vertical videos and uploads them to a single YouTube channel.

**Channel:** [GTA 6 Viral Moments](https://www.youtube.com/channel/UCTyGxG-QYWMuPqSobydMxog)

**Operator:** David Knapp · dknapptravels@gmail.com

---

## Policies

- **[Privacy Policy](privacy-policy.md)**
- **[Terms of Service](terms-of-service.md)**

---

## What this is

A single-operator tool, run from the command line on one personal computer. It
is not distributed, not offered as a service, and has no users other than its
owner.

It processes only footage the operator recorded himself. It does not download
or scrape video from other creators or from any platform.

## What it does

1. Reads a gameplay recording from local storage
2. Transcribes the speech and detects notable moments in the audio and video
3. Selects short segments and writes titles and descriptions for them
4. Renders each one as a vertical video with captions
5. Uploads it to the operator's own channel as a **private** video and sets a
   scheduled publication time
6. Reads back view counts for the operator's own published videos

## YouTube API use

This tool uses YouTube API Services, requesting three scopes:

| Scope | Why |
|---|---|
| `youtube.upload` | Upload videos to the operator's own channel |
| `youtube.readonly` | Check whether an upload finished processing |
| `yt-analytics.readonly` | Read view counts for the operator's own videos |

It accesses no channel other than the operator's own.

Its operator is bound by the [YouTube Terms of Service](https://www.youtube.com/t/terms)
and the [Google Privacy Policy](https://policies.google.com/privacy). Access can
be revoked at any time at
[myaccount.google.com/permissions](https://myaccount.google.com/permissions).

## What it will never do

No view inflation, no artificial engagement, no bot comments, no interaction
with other users or channels, and no access to anyone else's data.

---

This repository holds the published policies for the tool. The tool's own
source code is kept in a separate private repository.
