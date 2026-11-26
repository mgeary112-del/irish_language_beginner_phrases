# Irish Flashcards

A phone-friendly flashcard app. English phrase on the front, Irish on the back, with audio from abair.ie.

The site contains only the app and the phrase list. It does not include or redistribute any abair.ie audio.
Each device fetches clips from abair.ie as you use the app and keeps its own copy in the browser.

## Publish on GitHub Pages

1. Create a new repository on GitHub with a non-obvious name (the site is public to anyone who has the link).
2. Upload every file in this folder to the repository root (index.html must be at the top level).
3. Go to Settings > Pages. Under "Build and deployment", set Source to "Deploy from a branch", choose the `main` branch and the `/ (root)` folder, then Save.
4. After a minute, your site is live at `https://<your-username>.github.io/<repository-name>/`.

## Use it on your phone

- Open the link, then use the browser's "Add to Home Screen" (iOS Safari: Share > Add to Home Screen).
- In the app, tap "Download all audio for offline use" once on Wi-Fi to save every clip on that device.
- Each device you use needs to do this once, because saved audio stays on that device.

## Notes

- `sw.js` caches the app so it opens offline. Bump `CACHE` in it (e.g. `irish-flashcards-v2`) when you want everyone to pick up a big change.
- Please be considerate of abair.ie's free service: the app only requests each phrase once per device.
