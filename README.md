<p align="center">
  <img src="icon.png" width="80" alt="Speedybara logo" />
</p>
<h1 align="center">Speedybara</h1>

<p align="center">
  <strong>Speed up AFK Journey — on PC or emulator — with one slider.</strong><br>
  Native Windows • Simple • No background slowdown
</p>

<p align="center">
  <a href="https://github.com/kevin940726/speedybara/releases/latest"><img src="https://img.shields.io/github/v/release/kevin940726/speedybara?label=latest%20stable&color=0ea5e9" alt="latest stable"></a>
  <a href="https://github.com/kevin940726/speedybara/releases"><img src="https://img.shields.io/github/v/tag/kevin940726/speedybara?label=beta&include_prereleases&color=8b5cf6" alt="beta"></a>
  <a href="https://github.com/kevin940726/speedybara/releases"><img src="https://img.shields.io/github/downloads/kevin940726/speedybara/total?color=10b981" alt="downloads"></a>
  <img src="https://img.shields.io/badge/Windows-10%2F11%20x64-0078d6" alt="Windows 10/11 x64">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="MIT">
</p>

<p align="center"><a href="https://github.com/kevin940726/speedybara/releases/latest">⬇ Download latest release</a> • <a href="#-quick-start">Quick Start</a> • <a href="#-features">Features</a> • <a href="#-caveats">Caveats</a></p>

> **Current version:** `v1.2.0` stable • `v2.0.0-beta.1` prerelease — prereleases are not auto-offered to stable users.

---

## ✨ Features

- ⚡ **Speed `0.25×` → `8×`** — drag to preview, release to apply; each window shows its own current speed
- 🎯 **Per-window speed** — PC and each emulator window keep their own setting, so you can run one at `1×` and another at `3×`
- ⌨️ **Hotkeys that stay out of the way** — `F1`–`F4` by default (`1×` / `2×` / `0.5×` / `3×`); only active when AFK Journey or Speedybara is focused
- 🔧 **Easy to change** — rebind any key combo (`Ctrl`/`Shift`/`Alt` supported), hold-to-burst with “Stop on release”
- 🖥️ **Multi-window** — see every running AFK Journey, click a row to bring that window forward
- 📱 **Emulator support** — MuMu / BlueStacks / LDPlayer / Nox / MEmu, auto-detected and shows emulator name (e.g. `MuMu • 7555`)
- 🛡️ **Safe by default** — returns to `1×` when you close or detach, so the game doesn’t crash
- 📝 **Simple log** — auto-scrolls, pauses when you select text, with copy/clear and daily log files

---

## 📋 Requirements

| Need | Detail |
|------|--------|
| **OS** | Windows 10/11, 64-bit |
| **Run as** | **Administrator** (required to control the game) |
| **Game** | AFK Journey (PC 64-bit *or* Android emulator) |
| **Emulator** | Must be **rooted** — MuMu: System → Enable root; LDPlayer/Nox: Settings → Root; BlueStacks: Root toggle |
| **In-game** | **Turn V-Sync OFF** in Graphics settings (required) |

---

## 🚀 Quick Start

1. **Download** `Speedybara.exe` from [Releases](https://github.com/kevin940726/speedybara/releases/latest).
2. **Right-click → Run as administrator** → accept the prompt. First run: if Windows shows SmartScreen, click `More info` → `Run anyway` (one-time, app is not code-signed).
3. **Start AFK Journey** (on PC, or in your rooted emulator).
4. **Pick the game window** in Speedybara → drag the slider or press a hotkey. Hold a “Stop on release” key for a temporary burst.

---

## ⚠️ Caveats / Before you start

- 🔐 **Admin is required** — without it the speed control can’t attach. Your antivirus may flag the app the first time — allow it if needed.
- 🖼️ **V-Sync must be OFF** — with V-Sync on, the game locks to your monitor and the speed has no effect. Turn it off in Game → Graphics.
- 🧩 **64-bit only** — 32-bit game/emulator shows “Not supported”.
- 📱 **Emulator must be rooted** — if you see `⚠ Not rooted — enable root`, turn on root in the emulator and restart it.
- ♻️ **One slider per emulator** — two game accounts in the *same* emulator share the same speed.

---

## 🔧 Troubleshooting

| Problem | Try this |
|---------|----------|
| **No game found** | Start the game first, then click `Refresh` in Speedybara. |
| **Emulator not listed** | Make sure the emulator is running and rooted; try restarting it. |
| **`Failed to open` / attach failed** | Run Speedybara as Administrator and close other tools that control the game. |
| **Hotkeys do nothing** | Use a key combo no other app uses; they only work when the game or Speedybara is focused. |
| **Game crashes on exit** | Should return to `1×` automatically — if not, send the log file. |
| **`Failed to extract` / antivirus warning** | Allow `Speedybara.exe` in your antivirus; make sure your temp folder is writable. |
| **Speed jumps back to `1×`** | Another Speedybara window was closed (it resets that game to `1×`). |

> Log files: `%LOCALAPPDATA%\Speedybara\logs\` (one per day) plus the in-app log.

---

## 📜 Disclaimer

- **Unofficial** — not made or endorsed by Farlight / Lilith or any emulator maker. For personal and educational use.
- **Use at your own risk** — speeding up the game may break the game’s rules and could affect your account. No warranty.
- **Private by design** — works offline, no data is sent anywhere. Settings stay on your PC (`%LOCALAPPDATA%\Speedybara\`).
- **Need help?** — please don’t contact the game’s support; open an issue at [kevin940726/speedybara/issues](https://github.com/kevin940726/speedybara/issues) and include the log.

---

## 📄 License

MIT.
