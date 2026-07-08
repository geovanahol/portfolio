# Geovana Holaten — Portfolio

Static site. No build step. Just publish these files.

## Folder structure
```
index.html          ← the whole site (open this)
support.js          ← runtime — MUST sit next to index.html
images/             ← project images
game/               ← Pawtion Shop (Godot web build)
```

## Publish on GitHub Pages
1. Create a repository and upload EVERYTHING in this folder (keep the structure).
2. Repo → Settings → Pages → Source: branch `main`, folder `/root` → Save.
3. Live in ~1 min at `https://<your-username>.github.io/<repo-name>`.

## ⚠️ Pawtion Shop game — two files to add yourself
The Godot build needs two large files that are NOT included here (they're over the
upload limit). Copy them from your Godot export into the `game/` folder before publishing:

- `game/PawtionShop.wasm`  (~35 MB)
- `game/PawtionShop.pck`   (~38 MB)

These exceed GitHub's 25 MB web-upload limit, so add them with **GitHub Desktop** or
**git** (both allow up to 100 MB per file). Once they're in `game/`, the in-page
"▶ Play game" button on the Pawtion Shop page works automatically.

## Update contact / social
Email and LinkedIn are set in the Contact section. Edit `index.html` to change them.
