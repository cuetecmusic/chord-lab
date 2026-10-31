# Chord Lab by Cuetec — Web Edition 2.3

This folder is the standalone browser edition extracted from the Android 2.3 project.

## Run locally

For a quick test, serve this folder over localhost (service workers require localhost or HTTPS):

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in a modern browser.

## Publish and share

Upload the complete contents of this folder to a static HTTPS host, for example GitHub Pages, Netlify, or Cloudflare Pages. The public HTTPS URL is the share link. No server or database is required for the core instrument.

## Browser notes

- Audio uses the Web Audio API. Tap a pad or start playback once to unlock audio in the browser.
- Preset/session save downloads a JSON file; loading uses the browser file picker.
- Browser MIDI availability depends on browser, operating system, device and secure-context support. Native Android MIDI bridge functions are not included in the browser edition.
- Session files are stored on the user's device when downloaded; there is no shared cloud preset storage or user account system.
- Offline caching is enabled after the first successful visit on HTTPS/localhost.
