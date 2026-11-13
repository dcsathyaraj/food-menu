[README.md](https://github.com/user-attachments/files/34819392/README.md)
# Thanikssha Foods & Sweets LLC - Menu Site

A single-page static menu with category filters and search. No build step.

## Files
- `index.html` - the whole site (HTML, CSS and JS in one file)
- `render.yaml` - Render Blueprint that deploys it as a free static site

## Deploy on Render
1. Push this folder to a GitHub repository.
2. In Render, choose **New > Blueprint** and select the repository.
3. Render reads `render.yaml` and publishes the site at `https://thanikssha-menu.onrender.com` (or a similar name if taken).

Or without the Blueprint: **New > Static Site**, connect the repo, leave the build command empty and set the publish directory to `.`.

## Edit the menu
Open `index.html` and change the `MENU` list near the bottom. Each category has a name, icon, color and items. An item can be plain text, or `["Name", "note"]` to show a small note under it. Commit and push, and Render redeploys automatically.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server 8000` in this folder.
