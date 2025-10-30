# Fantasy Adventure

An HTML and CSS project for MMP100.

## What I added

- `index.html` — a simple GitHub Pages preview page (already in main).
- `styles.css` — starter stylesheet to replace the inline fallback styles.
- `assets/logo.svg` — small vector logo used by the page.

## How to publish on GitHub Pages

1. In the repository on GitHub, open Settings → Pages.
2. Under "Build and deployment", choose "Deploy from a branch".
3. Select the `main` branch and the `/ (root)` folder, then Save.
4. Wait a minute or two and visit:
   `https://titusdanielstd-netizen.github.io/fantasyadventure/`

## To add these files locally and push to branch X

# create branch locally (if you don't already have it)
git fetch origin
git checkout -b X origin/X

# create files (or copy the contents above into the files)
mkdir -p assets
# (create styles.css, assets/logo.svg, index.html, README.md)

git add styles.css assets/logo.svg index.html README.md
git commit -m "Add starter styles, logo, and updated index for GitHub Pages"
git push -u origin X

## Next steps you can ask me to do
- Push these prepared files directly into branch "X" (I’ll commit them there).
- Create a pull request from branch "X" into "main".
- Add sample images into assets/, or modify the design/layout further.
