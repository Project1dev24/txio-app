# Txio App — Official Web Landing Page & Public Releases

This repository hosts the official web landing page and public release binaries for **Txio — Autonomous Personal Expense Tracker & Financial OS**.

- **Live Landing Page**: Hosted on GitHub Pages
- **Public Releases**: Available under GitHub Releases (`releases/latest/download/txio-latest.apk`)

## Architecture

This is a public mirror repository decoupled from the private development codebase (`personal-expense-tracker`).
- Built APK and IPA binaries are automatically published to GitHub Releases via CI workflows.
- `versions.json` dynamically provides metadata for latest release links and version tags on `index.html`.
