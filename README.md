# ARCSTUDIO AI — Public Media Host and Content Archive

This repository hosts final, approved, publicly shareable ARCSTUDIO91 Instagram media and the minimal public post manifests needed to identify and audit each package.

- Account: @arcstudio91
- Platform: Instagram only
- Buffer channel: `arcstudio91`
- Default branch: `main`

## Folder layout

Each publishing date has its own folder:

`YYYY-MM-DD/`
- `feed.jpg` — one single-image feed post
- `carousel-01.jpg` … `carousel-04.jpg` — four slides in reading order
- `reel.mp4` — one vertical Reel
- `post-manifest.json` — captions, alt text, source notes, asset paths, raw URLs, QA and Buffer post IDs/status

Private PNG masters, source scripts, editable projects, raw footage and ZIP packages remain in the private delivery/workspace location and must not be uploaded here.

## Publishing rules

1. Upload only final, approved, publicly shareable media and the corresponding public post manifest. This repository is public; everything committed here can be accessed by anyone.
2. Never upload credentials, private client/project files, personal data, drafts, private production notes, full ZIP packages, editable source projects, or unlicensed third-party assets.
3. Use unique dated paths. Keep previously published media and manifests as a persistent archive. **Do not delete assets after Buffer has sent a post**; the user has now requested this repository as the long-term content store, superseding the earlier post-send media-cleanup instruction.
4. Use direct, anonymously downloadable raw GitHub HTTPS file URLs for Buffer media only after verifying the exact URL returns the actual non-empty binary with the expected media type. A GitHub page URL, preview page, placeholder, source-code file, or guessed URL is not a valid media asset.
5. Use Buffer's connected Instagram Business channel for @arcstudio91 only. Queue using automatic publishing; verify every returned post ID in Buffer. A queued post is not yet published.
6. Record the Buffer ID, scheduling/publishing status, sent time (if any), asset paths and verification results in the dated manifest and root `content-index.json`.
7. If a media binary cannot be transferred exactly to this repository or its raw URL cannot be verified, do not submit that item to Buffer. Continue the content package, keep the daily task enabled and record the specific blocker.

## Content index

`content-index.json` is the persistent machine-readable index of dated content packages. Append new entries; never replace or truncate the history.
