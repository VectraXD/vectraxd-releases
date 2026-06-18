# VectraXD Preview — User Guide

**Free desktop 3D file viewer for macOS, Windows, and Linux.**

Open GLB, GLTF, OBJ, PLY, IFC, DXF, and Gaussian Splat files instantly — no account required, no cloud upload.

---

## Download & Install

Get the latest version from the [Releases page](https://github.com/VectraXD/vectraxd-preview/releases/latest).

### macOS

| Chip | File |
|---|---|
| Apple Silicon (M1–M4) | `VectraXD Preview-x.x.x-arm64.dmg` |
| Intel | `VectraXD Preview-x.x.x.dmg` |

1. Open the `.dmg` and drag **VectraXD Preview** to your Applications folder.
2. On first launch: right-click the app → **Open** to bypass Gatekeeper (only needed once).

### Windows

Run `VectraXD Preview Setup x.x.x.exe`. Choose your install directory when prompted. Desktop and Start Menu shortcuts are created automatically.

### Linux

**AppImage:**
```bash
chmod +x "VectraXD Preview-x.x.x.AppImage"
./"VectraXD Preview-x.x.x.AppImage"
```

**Snap:**
```bash
snap install --dangerous vectraxd-preview_x.x.x_amd64.snap
```

---

## Supported File Formats

| Extension | Format |
|---|---|
| `.glb` `.gltf` | GL Transmission Format — 3D scenes and models |
| `.obj` | Wavefront OBJ — 3D mesh |
| `.ply` | PLY — point cloud / mesh |
| `.ifc` | IFC — BIM / architectural models |
| `.dxf` | DXF — CAD drawings |
| `.splat` | Gaussian Splat — radiance field capture |

---

## Opening Files

Three ways to open a file:

**Drag and drop** — drag any supported file onto the app window. The background highlights to confirm it's ready to drop.

**Open dialog** — click **Open File…** on the welcome screen, or use the folder icon in the toolbar, or go to **File → Open** in the menu bar.

**File association** — double-click a supported file in Finder / File Explorer. VectraXD Preview registers itself as the default viewer for all supported extensions on install.

---

## Recent Files

The welcome screen shows your last 10 opened files with relative timestamps. Click any entry to reopen it immediately.

To remove the history, click **Clear** next to the Recent heading.

---

## Theme

Toggle between light and dark mode:
- Click the moon/sun icon in the footer (bottom-right).
- Or use **View → Toggle Theme** from the menu bar.

The preference is saved and restored on next launch.

---

## Updates

VectraXD Preview checks for updates automatically in the background. When a new version is available:

1. A banner appears at the top of the window.
2. The update downloads automatically.
3. Click **Install Update** — the app restarts and applies the update.

---

## System Requirements

| Platform | Minimum |
|---|---|
| macOS | 10.15 Catalina or later |
| Windows | Windows 10 (x64) or later |
| Linux | glibc 2.17+ (most distros since 2014) |

A dedicated GPU improves rendering performance for large or complex models, but is not required.

---

## Telemetry & Privacy

VectraXD Preview collects anonymous usage analytics to help improve the product.

**What is collected:**
- App launch events
- File format opened (e.g. "glb") and file size

**What is never collected:**
- File contents or filenames
- Personal information
- Network or system data

**Opt out:** click the bar-chart icon in the bottom-right footer at any time. The setting is stored locally and persists across restarts.

---

## Troubleshooting

**macOS: "VectraXD Preview can't be opened because Apple cannot check it for malicious software"**
Right-click the app icon → **Open** → **Open** again in the dialog. This is a one-time step for apps distributed outside the Mac App Store.

**File opens but nothing renders**
- Check the file is not corrupted by opening it in another tool.
- For `.ifc` files, very large models (100MB+) may take several seconds to parse.

**App reports a viewer error on launch**
The app requires a network connection on first run to register the device. Ensure internet access is available, then relaunch.

---

## Feedback & Issues

Report bugs or request features on the [Issues page](https://github.com/VectraXD/vectraxd-preview/issues).

---

Copyright © 2020–2026 Prolincur Technologies LLP. All rights reserved.
