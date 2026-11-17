MIXOLOGY ACADEMY — PROJECT STRUCTURE

index.html                 Main website structure
styles.css                 All visual styling and responsive layout
content.js                 Educational content (topics, glassware, spirits, wines, beer, syrups)
app.js                     Renders content, filters spirits, searches topics, registers service worker
service-worker.js          Offline cache (works when hosted over HTTPS or localhost)
manifest.webmanifest       Installable web-app metadata
assets/icons/              App and browser icons
assets/images/spirits/      Put spirit-related image files here
assets/images/glassware/   Put glassware image files here

HOW TO USE
1. Upload the entire contents of this folder to one GitHub repository, keeping the folder structure.
2. Enable GitHub Pages or connect the repository to Netlify.
3. Open the deployed HTTPS website once while online so the service worker can cache the core files.
4. Reload, then test offline.
5. If you change core file names, update the FILES list in service-worker.js and change CACHE version (e.g. mixology-academy-v2).

IMAGE RULES
- Keep spirit photos in assets/images/spirits/
- Keep glass photos in assets/images/glassware/
- Keep icons in assets/icons/
- Use relative paths in HTML/CSS/JS. Do not rename folders unless you update every path.

NOTES
- The Google Fonts import is optional; the site falls back to system fonts if offline.
- This is an educational starter curriculum, not a substitute for local licensing rules, product labels, venue recipes or professional training.
- Some spirit and wine definitions are governed by regional legal standards. Always check the relevant country's rules.
