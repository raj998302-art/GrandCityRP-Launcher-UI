# Grand City RP Launcher — UI/UX Demo (Android, Native Java)

<p align="center"><b>Cyberpunk neon launcher UI — landscape, fully animated, 100% native Java (no WebView)</b></p>

## Screens
| # | Screen | Highlights |
|---|--------|-----------|
| 1 | Splash | Crown pop-in, GRAND/CITY slide, RP rotate-in, neon loading bar |
| 2 | Loading | Rotating gradient ring, cycling tips, progress |
| 3 | Login | Glass form, staggered fields, shine-sweep button — **bypassed** |
| 4 | Register | 4 fields + Google/Discord buttons |
| 5 | Home | Profile, stats, quick play, news & settings tabs, animated bottom nav |
| 6 | Server Select | Filter chips, glowing server cards |
| 7 | Spawn Select | Animated map pins, 6 locations |
| 8 | Connecting | Gradient ring, sequential checkmarks, WELCOME TO LOS SANTOS |

## Design System
- Colors: cyan `#00E5FF` · purple `#7861FF` · pink `#FF3ED7` · green `#00FF88`
- Fonts: **Orbitron** (headings) · **Poppins** (body) · **Pacifico** (script)
- Effects: particles, Ken Burns, neon glows, glassmorphism, shine sweeps

## Download
Grab the APK from the [Releases](../../releases) page → `GrandCityRP-UI-Demo-v1.0.apk`

**Requirements:** Android 7.0+ (API 24). Login is bypassed — just tap LOGIN.

## Build
Manual toolchain build (aapt2 + javac + d8 + apksigner):
```bash
./build.sh   # produces dist/GrandCityRP-UI-Demo-v1.0.apk
```

## Credits
Built from the Grand City RP design spec. UI/UX demo only — no game logic.
