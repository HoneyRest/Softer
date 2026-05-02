# Softer — Buyer setup guide

## What this product is

**Softer** is a **private web app** for a calm home dashboard: gentle resets, rituals, and daily rhythm in one page. It works in any modern browser on phone, tablet, or desktop.

This is a **private web app. No login, no subscription.** Your entries save **locally in your browser** on the device you use.

---

## How to open the hosted app link

After your seller publishes the app to static hosting (for example **GitHub Pages**), you’ll receive a URL such as:

`https://your-name.github.io/your-repo-name/`

1. Open that link in **Safari** (iPhone/iPad) or **Chrome**, **Safari**, or **Firefox** (desktop).
2. The app loads from **index.html** at that address—no App Store install required.

---

## Add to Home Screen (iPhone / iPad)

1. Open the hosted link in **Safari**.
2. Tap the **Share** button (square with arrow).
3. Scroll and tap **Add to Home Screen**.
4. Edit the name if you like, then tap **Add**.

You’ll get a home-screen icon (uses **softer-icon.png** when deployed with that file). Opening from the home screen feels more like a standalone app.

---

## Use on desktop

1. Open your hosted link (or open **index.html** directly if you downloaded the files).
2. **Bookmark** the page for quick access.
3. Use **full-screen** or **windowed** mode like any website—your data stays in that browser profile.

---

## Privacy & local storage

**This is a private web app. No login, no subscription.** Your entries save **locally in your browser** on the device you use.

- Data is stored with **browser local storage** on that device.
- Data **does not leave your device** through this app’s normal operation (there is no server account).

### Important warning

**If you clear browser data or switch devices, export a backup first.** Clearing site data or using a different browser/device **does not** move your entries automatically.

---

## Backup & restore (export / import)

### Export (backup)

1. Open **Softer**.
2. Find the **backup / export** option in the app’s settings or tools area (wording may vary by version).
3. Export downloads a JSON file, typically named **`softer-backup.json`**.
4. Save that file somewhere safe (cloud drive, email to yourself, USB).

### Import (restore)

1. Open **Softer** on the device/browser where you want data.
2. Use **Import backup** and choose the JSON file you exported from Softer.
3. Confirm any prompts—import usually **replaces** existing data in that browser.

Use backups when **changing phones**, **reinstalling the browser**, or **moving between computers**.

---

## Troubleshooting

| Issue | What to try |
|--------|----------------|
| Blank or stuck loading | Hard refresh (desktop: Ctrl+F5 / Cmd+Shift+R). Try another browser. |
| “Works offline” but icons/fonts look different offline | Ensure **softer-icon.png** is in the **same folder** as **index.html** on your host. |
| Data missing after phone restore | Data was tied to the old browser profile—restore from your **`softer-backup.json`** if you exported one. |
| Private / Incognito mode | Some browsers limit or clear storage—use a normal window for long-term journaling. |
| GitHub Pages 404 | Confirm **index.html** is at the **repository root** and Pages is enabled for the correct branch. |

If something still fails, note your **browser name and version** and whether you’re on **iOS, Android, Mac, or Windows** when asking for help.
