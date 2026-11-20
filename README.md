# WuWa Engine.ini — Balanced (Intel Arc B580)

Enhanced config for **Wuthering Waves**: balanced visuals + performance on Intel Arc B580.

**Performance:** High/Ultra + 2x Frame Generation + RT Low → ~100–150 FPS

## Contents

- `Config/Engine.ini` — custom Engine.ini (shadows, AO, foliage, streaming, RT).
- `In-Game Settings/Settings.md` — recommended in-game graphics settings.
- `Global Filters/Default.md` — default global filter (color palette).

## Installation

Replace the `Engine.ini` in the following path:

**Steam:**
```
...\Wuthering Waves\Wuthering Waves Game\Client\Saved\Config\WindowsNoEditor\
```
Delete `UserEngine.ini` if it exists in `Client\Config`.

## Steam Launch Options (optional, skip launcher)
```
"C:\SteamLibrary\steamapps\common\Wuthering Waves\Wuthering Waves Game\Client\Binaries\Win64\Client-Win64-Shipping.exe" %command% -krqlv=uhd -SkipSplash
```

## Notes
- Target: Arc B580 @ 1080p (UHD preset). Lower Render-Distance/Foliage/LOD in 1440p or if lagging.
- Keep **Auto FPS off**; use XeSS3 + 2x FG + RT Low.
- Keep backup of original Engine.ini in case of issues.
