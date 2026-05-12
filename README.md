# iPhone Messages Emulator

A single-file iOS Messages emulator for recording fake-chat videos. Type a `Speaker: message` script, pick a POV, hit play.

- **Light / Dark** toggle in the controls sidebar
- **Inline media library** — click `+ 📷 / + 🎞 / + 🎬` above any script textarea to upload a photo / animated GIF / video poster; a `[gif:NAME]` marker is inserted at the cursor
- **Easy + Advanced** script formats (auto-detected)
- **Recording mode** hides the controls and fills the viewport for clean screen captures

## Local dev

Just open `emulator.html` in a browser, or serve it:

```bash
python -m http.server 8000
# then visit http://localhost:8000/
```

## Deploy

This is a static site — `index.html` redirects to `emulator.html`. Push to GitHub and import the repo in Vercel; no build step needed.
