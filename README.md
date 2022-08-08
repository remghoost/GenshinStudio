# Future of the Project

Vote here: https://forms.gle/NXLkxiDPekmUjmbHA

Looking forward for your feedback.
_____________________________________________________________________________________________________________________________
# GenshinStudio
Check out the [original AssetStudio project](https://github.com/Perfare/AssetStudio) for more information.

This is the release of GenshinStudio, Modded AssetStudio that should work with Genshin Impact/YuanShen.

Note: Requires Internet connection to fetch asset_index jsons.
_____________________________________________________________________________________________________________________________

Some features are:
```
- Integration with "Radioegor146" repo to load asset_index through "Options -> Specify AI version".
- Exportable Assets (not all of them) with XOR/JSON support for "MiHoYoBinData"
- Togglable debug console.
- Container/filename recovery for Assets.
- Build Asset List of assets inside game files (use "Option -> Export Options -> AM Format" to change between XML and JSON).
- CLI version (beta).
```
_____________________________________________________________________________________________________________________________
How to use:

```
1. Build BLK Map (Misc. -> Build BLKMap).
2. Load BLK files.
```

CLI Version:
```
AssetStudioCLI 0.16.55
Copyright (C) 2022 AssetStudioCLI

  -v, --verbose           Show log messages.

  -t, --type              Specify unity type(s).

  -f, --filter            Specify regex filter(s).

  --help                  Display this help screen.

  --version               Display version information.

  input_path (pos. 0)     Required. Input file/folder.

  output_path (pos. 1)    Required. Output folder.
```

NOTE: in case of any `MeshRenderer/SkinnedMeshRenderer` errors, make sure to enable `Disable Renderer` option in `Export Options` before loading assets.

Looking forward for feedback for issues/bugs to fix and update.
_____________________________________________________________________________________________________________________________
Special Thank to:
- Perfare: Original author.
- Khang06: [genshinblkstuff](https://github.com/khang06/genshinblkstuff) for blk/mhy0 extraction.
- Radioegor146: [gi-asset-indexes](https://github.com/radioegor146/gi-asset-indexes) for recovered/updated asset_index's.
- Ds5678: [AssetRipper](https://github.com/AssetRipper/AssetRipper)[[discord](https://discord.gg/XqXa53W2Yh) at `#genshin` channel] for information about Asset Formats & Parsing.
