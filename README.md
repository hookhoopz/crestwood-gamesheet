# Crestwood Prep Gamesheet (PWA)

Courtside stat tracker that installs to your home screen and works with no signal.

## Files
- index.html: the gamesheet app
- manifest.json: name, icon and colours for the home-screen install
- sw.js: offline worker that saves the app on your phone
- icon-*.png, apple-touch-icon.png: home-screen icons

## Put it online (GitHub Pages, free)
1. Create a GitHub account at github.com.
2. New repository, e.g. `crestwood-stats`, set to Public.
3. Add file > Upload files, drag in everything from this folder, Commit.
4. Settings > Pages > Source: Deploy from a branch > main / (root) > Save.
5. After a minute, open https://YOUR-USERNAME.github.io/crestwood-stats/

## Install on a phone
- iPhone: open the link in Safari > Share > Add to Home Screen.
- Android: open in Chrome > menu > Install app (or Add to Home screen).
Open it once while online; after that it opens with no connection.

## Updating
Edit index.html, then change VERSION in sw.js (gamesheet-v1 to gamesheet-v2) and upload both.
Phones pick up the new version the next time they open it online.

## Notes
- Stats are stored on each phone. Use Copy gamesheet to move a game into Sheets or Excel.
- Clearing Safari/Chrome website data erases saved games.
