# ipa-dist

Public distribution endpoint for the IPA Resign Bot.

- **Releases** here hold resigned `.ipa` files and their `manifest.plist` (uploaded automatically by the private `ipa-bot` repo's resign job).
- **`docs/install.html`** is served via GitHub Pages and bridges a manifest URL to the `itms-services://` OTA install on iOS.

This repo contains **no source and no secrets**. Enable GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / `/docs`**.

Downloads are public, but a resigned ad-hoc IPA only **installs** on devices registered in the signing Apple account.
