# Project Cinders

English settings, a fast TV home and an English quick panel over HDMI for Chinese-market XGIMI projectors.

**Website:** https://projectcinders.com · **Features:** https://projectcinders.com/en/features/ · **Install:** https://projectcinders.com/en/install/

This repository is the public home for Project Cinders: issue reports, feature requests, compatibility reports and the changelog. The app's source code is not published here.

## What it does

- English settings for picture, motion, 3D, HDR, projection, light, sound and HDMI, with help text on every row.
- An English quick panel that opens over HDMI video.
- A fast English launcher. The XGIMI launcher stays installed and is one click away.
- Curated apps from official sources (SmartTube, Jellyfin, Kodi, VLC and more), with no Google Play needed.
- Cleanup tiers that disable ads and bundled extras. Nothing is deleted, and restore is one click.
- Switches the system language to English and back exactly, with a Chinese glossary for the remaining stock screens.
- Available in English, Русский, Українська, Deutsch, Français, Español, Português (Brasil), Italiano, Polski and Türkçe.

No root needed. It never touches calibration, white balance, EDID, factory menus or firmware.

## Compatibility

Built for XGIMI projectors, with native support for the **RS30 Pro Flagship Edition** and similar models. Other XGIMI models are in early access: the app reads each projector's controls from its firmware, so try it free for 7 days and check **System → Compatibility** before you buy.

Own a different model? A [compatibility report](../../issues/new?template=compatibility.yml) helps a lot.

## Getting help

- **Bugs and projector problems:** in the app, use the report option. It sends diagnostics privately, and you can add photos from your phone by scanning the QR code. You can also [open an issue](../../issues/new/choose) here, but don't post license keys or order details.
- **Keys, orders, refunds and transfers:** https://projectcinders.com/en/manage/ or https://projectcinders.com/en/support/.
- **Security issues:** see [SECURITY.md](SECURITY.md).

## Verify your download

Only install the official APK from https://projectcinders.com/en/install/. Every release is signed with the same key, whose certificate SHA-256 is:

```
89:A8:C5:1B:CC:6F:66:6E:52:33:C2:72:FF:A2:79:5A:D8:7D:D2:7E:2D:80:6D:7C:3C:BC:6E:FB:6A:CF:CD:87
```

Check it with `apksigner verify --print-certs ProjectCinders.apk`. The app also checks this signer before installing its own updates.

## Known issues

- **Home asks which app to open after an update.** On XGIMI firmware, updating Project Cinders can sometimes reset Android's "Always" choice for the Home app. If pressing Home shows an "Opening method" chooser, select Project Cinders, then **Always** (始终). You only need to do this once after the update.

## Changelog

See [CHANGELOG.md](CHANGELOG.md) or https://projectcinders.com/en/changelog/.

Project Cinders is an independent product and is not affiliated with or endorsed by XGIMI.
