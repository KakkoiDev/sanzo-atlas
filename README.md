# Sanzo — A study in color

A standalone, build-free color atlas for GitHub Pages: 348 historical combinations, 159 colors, name/HEX search, 2/3/4-color filters, browser-local favorites, palette copying, and perceptual nearest-color matching in OKLab.

## Preview

From this directory run `python3 -m http.server 4173`, then visit http://localhost:4173. No install or build step is required. Google Fonts are optional; serif and sans-serif fallbacks work offline.

## Publish on GitHub Pages

Copy this directory's contents to a new GitHub repository. In that repository, choose **Settings → Pages → Deploy from a branch → main → / (root)**, then save. All asset paths are relative and work on both repository and custom-domain Pages sites. `.nojekyll` bypasses Jekyll.

This folder is an independent project, not a replacement for the surrounding Pi Workbench app.

## Credits

Sanzo Wada, *A Dictionary of Color Combinations*. Color data from [Matt DesLauriers](https://github.com/mattdesl/dictionary-of-colour-combinations), originally compiled by Dain M. Blodorn Kim. The upstream MIT license is preserved in `data/LICENSE.md`. Digital values approximate printed colors; this is an independent study, not an official publication.
