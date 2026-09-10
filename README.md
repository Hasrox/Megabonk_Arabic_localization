# Megabonk Arabic Localization

Fan Arabic patch for **Megabonk 1.0.69**.

Drag-and-drop install. No extra tools. Do not replace `settings.json`.

## Download

Get the pack zip from the latest GitHub Release:

**[Megabonk Arabic — game ver 1.0.69.zip](https://github.com/Hasrox/Megabonk_Arabic_localization/releases)**

That zip is already laid out as `Megabonk_Data/...` so you can drop it on the game folder.

## Install

1. Close Megabonk.
2. Open your game folder:
   - Steam: `steamapps/common/Megabonk/`
3. Extract the zip. You should see a `Megabonk_Data` folder.
4. Copy that `Megabonk_Data` folder onto the game folder and **merge / replace** when Windows asks.

Files this pack overwrites:

```
Megabonk_Data/sharedassets0.assets
Megabonk_Data/StreamingAssets/aa/catalog.json
Megabonk_Data/StreamingAssets/aa/StandaloneWindows64/localization-string-tables-english(en)_assets_all.bundle
```

Leave every other file alone. Especially **do not** replace `StreamingAssets/aa/settings.json`.

5. Launch the game. UI should be Arabic.

## Uninstall

Steam → Megabonk → Properties → Installed Files → Verify integrity of game files.

## Credits

- Original Arabic localization: **29TWK_DHM**
- Port / 1.0.69 pack: **[@CoralTwitcher](https://twitter.com/CoralTwitcher)**
- Repo: [Hasrox/Megabonk_Arabic_localization](https://github.com/Hasrox/Megabonk_Arabic_localization)

## Notes

- Built and tested against Megabonk **V 1.0.69** (2026-09-10).
- TextMeshPro in this build is LTR, so Arabic is stored as visual presentation-form text.
- Do not enable TMP Right-to-Left on this version (it crashes).
