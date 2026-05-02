# Softer

**Softer** is a private, single-page web app for a calmer home rhythm—daily resets, rituals, and gentle structure. Everything runs in your browser with **no backend, no login, and no database**.

## Contents of this folder

| File | Purpose |
|------|---------|
| `index.html` | The full app (open this in a browser or deploy as your site entry point). |
| `softer-icon.png` | Icon for bookmarks and “Add to Home Screen”. |
| `buyer-setup-guide.md` | Buyer-facing setup, privacy, backup, and troubleshooting. |

## Static hosting (GitHub Pages)

1. Create a **new GitHub repository** for this product (this folder can be the repo root).
2. Upload **all files** from this folder to the repository root (`index.html`, `softer-icon.png`, and the docs).
3. In the repo: **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, branch **main** (or **master**), folder **`/ (root)`**.
5. After deployment, GitHub shows your live URL (for example `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`).

GitHub Pages serves `index.html` automatically when someone visits that URL. Replace placeholders with your real username and repo name.

### Optional local preview

From this folder:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080/` in your browser.

## Privacy & data

This is a **private web app**. **No login, no subscription.** Your entries save **locally in your browser** on the device you use. Nothing is sent to a server by design.

**If you clear browser data or switch devices, export a backup first** (see `buyer-setup-guide.md`).

## Replacing the icon

Swap `softer-icon.png` with your own **square PNG** (recommended at least **512×512**). Keep the filename the same, or update the `<link rel="icon">` and `<link rel="apple-touch-icon">` paths in `index.html`.
