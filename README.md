# A Little Apology — GitHub Pages package

A 7-scene interactive apology website: one `index.html` plus the `assets/` folder
(photos, character art, teddies, and the song recording). No build step, no server needed.

## Publish it (free, ~2 minutes)

1. On GitHub, create a new **public** repository (any name, e.g. `a-little-apology`).
2. Upload **everything from this zip** to the repository's root: `index.html`,
   the `assets/` folder, and `.nojekyll`.
   - Web upload: in the repo, **Add file → Upload files**, then drag all of them
     in (drag the `assets` folder too, so the structure stays intact). Commit.
   - Or with git: clone the repo, copy these files in, `git add .`, `git commit`, `git push`.
3. In the repo, go to **Settings → Pages**. Under **Build and deployment → Source**,
   choose **Deploy from a branch**. Set Branch to `main` and folder to `/ (root)`. Save.
4. Wait about a minute. Your site is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Notes

- Keep `index.html` at the repo root and the `assets/` folder beside it, with file
  names unchanged — the page loads the song and photos from `assets/` using relative paths.
- `.nojekyll` tells GitHub Pages to serve the files exactly as-is.
- The page loads its fonts from Google Fonts, so viewers need an internet connection.
- The final scene links to a Google Form (already set in the page).
- The demo version in Muse stays available separately; this zip is the identical
  final site, ready to host yourself.
