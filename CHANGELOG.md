# Changelog

## 1.0.0
- First stable release of Nimble Simple Shop for Foundry VTT v14 and Nimble 0.10.0. No functional changes since 0.2.1.

## 0.2.1
- Version bump and re-release. No functional changes since 0.2.0.

## 0.2.0
- Forked from [KennyMakes/Nimble-Shop](https://github.com/KennyMakes/Nimble-Shop) as **Nimble Simple Shop** (module id `nimble-simple-shop`).
- Targets Foundry VTT v14 (verified 14.365) and the Nimble system 0.10.0.
- The shop sheet is now built on `DocumentSheetV2` instead of extending the core journal sheet, so changes to the v14 journal sheet's pages and sidebar can't break it.
- Each journal entry now gets its own shop window, so several shops can be open at once.
- Player shop controls are no longer disabled on journal entries the player can't edit.
- Shops created with the original Nimble Shop module are read automatically.
- Items priced in copper are converted to silver (rounded up) when imported into stock.
- Releases are built by a GitHub Actions workflow and installable from a manifest URL.

## 0.1.0
- First public release of Nimble Shop.
- Journal-backed storefront sheet for Nimble in Foundry VTT v13.
- GM editor for stock, hidden stock, custom orders, presets, and economy settings.
- Player buy, sell, hidden buy, and special-order flows.
- GM socket relay support for player transactions.
- Closed-shop storefront lockout and transaction guards.
