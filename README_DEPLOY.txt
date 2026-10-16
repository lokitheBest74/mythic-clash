MYTHIC CLASH — ART + MOBILE DEPLOY PACKAGE

WHY THE LIVE GAME SHOWS QUESTION MARKS
The current GitHub Pages repository must include the assets/ folder. The game loads its fighter portraits and arena using relative paths such as assets/sylvaine.jpg and assets/arena.jpg. If only index.html is uploaded, the interface loads but those images do not, which produces the broken-image/question-mark icons seen in the screenshot.

DEPLOY TO THE EXISTING GITHUB PAGES SITE
1. Open https://github.com/lokitheBest74/mythic-clash
2. On the main branch, upload/replace index.html from this package.
3. Upload the entire assets folder, preserving its name and all files inside it. Do not upload only the images individually into the repository root.
4. Commit the changes to main.
5. Wait for GitHub Pages to finish deploying, then reload https://lokitheBest74.github.io/mythic-clash/ (on iPhone, close the old page and reopen it if cached).

PACKAGE STRUCTURE
index.html
assets/arena.jpg
assets/battle-ui.jpg
assets/kael.jpg
assets/aurelia.jpg
assets/sylvaine.jpg
assets/seraphine.jpg
assets/darius.jpg
assets/sprite-kael.jpg
assets/sprite-aurelia.jpg
assets/sprite-sylvaine.jpg
assets/sprite-seraphine.jpg
assets/sprite-darius.jpg

CHECKS RUN
- Verified that all local image references used by the game have matching files in assets/.
- Extracted the JavaScript and ran Node's syntax check successfully.

NOTE
This is a deployment package, not a claim that the live GitHub Pages site has already been updated. The GitHub write integration did not grant permission to publish changes directly.
