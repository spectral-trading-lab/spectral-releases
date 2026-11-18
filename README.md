# Spectral

Spectral is a desktop trading app for Interactive Brokers: charts, watchlists, a trade manager for stocks and
options, and a trading journal.

**Website:** [spectral.trade](https://spectral.trade) · **Docs:** [Installation guide](https://spectral.trade/docs/installation)

This repository only hosts the signed installers and the update feed. The source code is not public.

## Download

Get the latest version from [Releases](https://github.com/spectral-trading-lab/spectral-releases/releases/latest):

| Platform | File |
| --- | --- |
| macOS, Apple Silicon (M1 and later) | `Spectral-macos-arm64.dmg` |
| macOS, Intel | `Spectral-macos-x64.dmg` |
| Windows 10/11, 64-bit | `Spectral-windows-x64-setup.exe` |

The `.zip`, `.yml` and `.blockmap` files are used by the built-in updater; you don't need to download them.

## Requirements

- macOS 13 or later, or Windows 10/11 (64-bit)
- An Interactive Brokers account with TWS or IB Gateway running
- A Spectral license. Spectral is currently in **beta**: access is by invitation, see [spectral.trade](https://spectral.trade).

## Updates

Spectral updates itself. Installers are signed (macOS: notarized Developer ID; Windows: signed by Dominik Germek).
On Windows, SmartScreen may ask once; check that the publisher is shown as **Dominik Germek**.

## Support

Questions or problems: [spectral.trade/contact](https://spectral.trade/contact). Please don't open GitHub issues here.
