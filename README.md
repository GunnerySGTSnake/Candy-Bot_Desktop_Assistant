# Candy-Bot Updates Repository

This repository hosts the auto-update system for Candy-Bot desktop application.

## Structure
```
├── index.html          # Download landing page
├── changelog.html      # Version changelog
├── update.xml          # AutoUpdater.NET manifest
├── downloads/          # Release ZIPs go here
│   └── CandyBot-Setup.zip
└── CHANGELOG.md        # Markdown changelog
```

## How to Release an Update

1. Build the new version of Candy-Bot
2. Create a ZIP of the build output
3. Place the ZIP in `downloads/CandyBot-Setup.zip`
4. Update `update.xml` with the new version number
5. Update `changelog.html` and `CHANGELOG.md`
6. Commit and push — Hostinger auto-deploys!

## Auto-Update Flow

1. Candy-Bot checks `update.xml` on startup
2. If a newer version exists, a dialog appears
3. User clicks "Update" → downloads the ZIP from `downloads/`
4. App extracts and updates automatically
