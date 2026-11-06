# Updating the already-published GitHub Pages website

Your repository: https://github.com/Erisehc/STAT236_Project_Website

You already use **main** + **/(root)**. You do NOT need a new repository, new branch, or docs folder.

## Easiest: the single-file update

1. Download `STAT236_Animated_OneFile_Update.zip` (provided separately).
2. Extract the `index.html` inside.
3. In your GitHub repository's **Code** tab (root folder), choose **Add file → Upload files** and upload the extracted replacement `index.html` to the root. Commit the update. If GitHub's web uploader does not permit overwriting an existing filename, replace `index.html` using GitHub Desktop / git, or edit the existing root file with the GitHub file editor.
4. Keep `assets/`, `data/`, and `report.pdf` exactly as they already are. No other uploads are necessary.
5. Visit https://erisehc.github.io/STAT236_Project_Website/ after the GitHub Pages workflow finishes. Hard-refresh if the old page is cached.

The one-file update contains all new animation CSS and JS inline, but still uses your existing project's original asset files.

## Alternative: the fully structured website ZIP

Extract `STAT236_Project_Website_Animated.zip` and replace the contents of your existing repository root with it. In particular the new files are:

- `index.html` (updated)
- `assets/simulation.js` (new)
- `assets/simulation.css` (new)

All other original project files are preserved. The version in this ZIP is easier to maintain if you want to edit the animation code later.

**Do not upload the ZIP itself as a single file.** GitHub Pages needs `index.html` and its related assets as ordinary repository files.
