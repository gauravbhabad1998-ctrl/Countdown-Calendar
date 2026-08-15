# Countdown Calendar PWA

This is a Progressive Web App version.

IMPORTANT: A PWA cannot be installed from a `file://` URL. It must be served over HTTPS (localhost is also allowed for testing).

## Quick local test

Python:
```bash
python3 -m http.server 8080
```
Then open:
http://localhost:8080/

For installation on an Android phone, deploy this folder to any HTTPS static web host. Open the HTTPS URL in Chrome and choose Install app / Add to Home screen.

## Files

- index.html — complete app
- manifest.webmanifest — installation metadata
- sw.js — offline caching/service worker

The app stores deadlines locally in the browser/device.
