# GHCHAIN Wallet Website

A professional Web3-style landing page + APK delivery for GHCHAIN Wallet.

## 📦 Contents
- `index.html` – static site (GitHub Pages ready)
- `assets/` – CSS, JS, images
- `dist/GHCHAIN_WALLET.apk` – placeholder APK (replace with real build)
- `LICENSE` – MIT
- `release_notes.md` – change log

## 🚀 Deploy to GitHub Pages
1. Create a new repo called **ghchain-wallet** under your GitHub (`berima1`).
2. Upload all files from this folder to the repository root.
3. Go to **Settings → Pages → Build and deployment** and set:
   - **Source:** Deploy from a branch
   - **Branch:** `main` / `/ (root)`
4. Your site will be live at: `https://berima1.github.io/ghchain-wallet/`

## 🧩 Permanent APK via GitHub Releases
1. Go to **Releases → Draft a new release**.
2. Tag: `v0.1.0-alpha` (or newer)
3. Upload `dist/GHCHAIN_WALLET.apk` as an asset.
4. Publish. Your permanent download link becomes:
   `https://github.com/berima1/ghchain-wallet/releases/latest/download/GHCHAIN_WALLET.apk`

Update the **Download** button in `index.html` if you change the filename.

## 🛡 Security Notes
- Never commit private keys or tokens.
- Sign APK builds before release.
- Use ProGuard/obfuscation for Android builds.
- Rotate any credentials shared during testing.

## 🧠 Contact
GHCHAIN Core — Africa-first • Military-grade • Multilingual.
