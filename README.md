# Bravent Plugin Store 🎮

Official plugin auto-update repository for **Bravent RhythmDeck** & **Bravent Hub**.

## Structure

```
bravent-plugin-store/
├── plugins/       # Plugin .sdPlugin.zip release files
├── updates/       # Auto-update manifest (for Bravent Hub updater)
└── README.md
```

## How Auto-Update Works

1. Bravent Hub checks `updates/manifest.json` for available updates.
2. Downloads the latest `.sdPlugin.zip` from `plugins/` or GitHub Release.
3. Validates SHA256 checksum.
4. Installs and creates backup for rollback.

## Support

- **Website**: [bravent.co](https://bravent.co)
- **Email**: sixth@bravent.co
- **Issues**: [GitHub Issues](https://github.com/sixth-tech/bravent-plugin-store/issues)

---
© 2026 Bravent. All rights reserved.