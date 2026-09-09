Arthur Morgan's Journal — V1.2

V1.2 adds bilingual quest help (English + Hungarian) to every unlocked mission.
The guide is spoiler-light and uses paraphrases rather than reproducing the game's full dialogue/objective text.

Files:
- index.html
- style.css
- app.js
- manifest.json
- sw.js

GitHub Pages:
1. Create a public repository.
2. Upload the files to the repository root.
3. Settings -> Pages -> Deploy from a branch -> main -> / (root).
4. Open the generated https://<username>.github.io/<repository>/ URL.

PWA note:
For the service worker to register correctly, open the site through HTTPS (GitHub Pages), not as a local file.

Progress:
The app uses localStorage and keeps the same save key. Export a JSON backup before switching devices or browsers.
