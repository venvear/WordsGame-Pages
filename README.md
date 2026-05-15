# Words Game Offline Pages

Static public pages for Words Game Offline: marketing, privacy policy, support, and terms. Marketing copy is kept aligned with the App Store listing (offline base-word puzzle, EN/RU/ES noun packs, coins, daily tasks, hints).

## Deploy

This repository deploys itself through `.github/workflows/pages.yml`.

GitHub repository settings:

- Pages source: GitHub Actions.
- Branch: `main`.
- Public App Store link: `https://apps.apple.com/app/id6768779867`.

The iOS app and App Store metadata currently point to:

- `https://venvear.github.io/WordsGame-Pages/`
- `https://venvear.github.io/WordsGame-Pages/privacy/`
- `https://venvear.github.io/WordsGame-Pages/support/`
- `https://venvear.github.io/WordsGame-Pages/terms/`

If this standalone pages repository is deployed under a different GitHub Pages path, update `AppConfig.swift` and `appstore/metadata.store.json` before submitting the app.
