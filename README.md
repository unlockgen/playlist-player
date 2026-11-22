# Playlist Player PWA

A static, installable iPhone web app. No backend or API key needed.

## Features
- YouTube playlist link validation and embedded playlist playback (foreground; subject to YouTube restrictions)
- Local saved playlist links
- Local audio file picker and direct authorized audio URL playback
- HTML audio and Media Session API for supported iPhone lock-screen playback
- Offline app shell via service worker (not offline YouTube content)

## Publish
Upload the contents of this folder to any HTTPS static hosting provider (GitHub Pages, Netlify, Cloudflare Pages). For GitHub Pages, place these files at the repository root and enable Pages from the main branch root. Open the HTTPS URL in Safari on iPhone, tap Share, then Add to Home Screen.

## Important
YouTube playback is provided only through the official embedded player. YouTube playback may stop when the phone locks or Safari goes into the background. This app does not download, extract, proxy, or bypass YouTube audio. Direct audio URLs must be authorized and playable by iOS; servers may block playback, and iOS background playback behavior can vary. Saved playlists are stored only in the browser's local storage.
