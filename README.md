<p align="center">
  <img src="https://raw.githubusercontent.com/Bridgology/bridgology-releases/assets/logo-light.png#gh-light-mode-only" alt="Bridgology" width="360">
  <img src="https://raw.githubusercontent.com/Bridgology/bridgology-releases/assets/logo-dark.png#gh-dark-mode-only" alt="Bridgology" width="360">
</p>

<h3 align="center">Ground-penetrating radar analysis for bridges, slabs and walls</h3>

<p align="center">
  Turn GPR surveys of concrete and masonry structures into thicknesses, cover depths and clear maps.
</p>

<p align="center">
  <a href="https://github.com/Bridgology/bridgology-releases/releases/download/v0.27.0/Bridgology-0.27.0-macos-arm64.dmg"><img src="https://raw.githubusercontent.com/Bridgology/bridgology-releases/assets/download-macos.svg" alt="Download for macOS" width="280"></a>
  &nbsp;
  <a href="https://github.com/Bridgology/bridgology-releases/releases/download/v0.27.0/Bridgology-0.27.0-windows-x64-setup.exe"><img src="https://raw.githubusercontent.com/Bridgology/bridgology-releases/assets/download-windows.svg" alt="Download for Windows" width="280"></a>
  <br>
  <a href="https://github.com/Bridgology/bridgology-releases/releases/download/v0.27.0/Bridgology-0.27.0-linux-x64.deb"><img src="https://raw.githubusercontent.com/Bridgology/bridgology-releases/assets/download-linux-deb.svg" alt="Download for Linux (.deb)" width="280"></a>
  &nbsp;
  <a href="https://github.com/Bridgology/bridgology-releases/releases/download/v0.27.0/Bridgology-0.27.0-linux-x64.AppImage"><img src="https://raw.githubusercontent.com/Bridgology/bridgology-releases/assets/download-linux-appimage.svg" alt="Download the Linux AppImage" width="280"></a>
</p>

<p align="center">
  <sub>Version 0.27.0 &nbsp;·&nbsp; Free Viewer included &nbsp;·&nbsp; <a href="../../releases">Release notes</a></sub>
</p>

<br>

<p align="center">
  <img src="https://raw.githubusercontent.com/Bridgology/bridgology-releases/assets/bscan-light.png#gh-light-mode-only" alt="Bridgology showing a radargram with picked asphalt and concrete layers" width="900">
  <img src="https://raw.githubusercontent.com/Bridgology/bridgology-releases/assets/bscan-dark.png#gh-dark-mode-only" alt="Bridgology showing a radargram with picked asphalt and concrete layers" width="900">
</p>

<br>

## What Bridgology does

Import a whole survey straight from your radar's files, pick the layers and rebars on the radargrams, and
Bridgology calculates thicknesses, depths, spacings and material properties, then maps them over the
structure, ready to export for your report.

### Read the radargrams

Clean up each scan with background removal, gain and filters, then pick layers, rebars and other features by
hand or automatically. Measure distances and times directly on the image.

### Place the scans on the site plan

Position every scan from its GPS or a spreadsheet, or set and correct the positions right on the plan, over a
drawing, a CAD plan, a photo or an online map of the site. Mark cores, joints, labels and areas to leave out.

<p align="center">
  <img src="https://raw.githubusercontent.com/Bridgology/bridgology-releases/assets/geometry-light.png#gh-light-mode-only" alt="Scan lines placed on the plan of a curved bridge" width="900">
  <img src="https://raw.githubusercontent.com/Bridgology/bridgology-releases/assets/geometry-dark.png#gh-dark-mode-only" alt="Scan lines placed on the plan of a curved bridge" width="900">
</p>

### Map the results

Thickness, cover depth, spacing and permittivity, interpolated into maps of the whole deck. Cut
cross-sections, outline areas of interest, and export the maps, the figures and the numbers to PDF, Excel or CAD.

<p align="center">
  <img src="https://raw.githubusercontent.com/Bridgology/bridgology-releases/assets/map-light.png#gh-light-mode-only" alt="Map of concrete thickness over a curved bridge deck" width="900">
  <img src="https://raw.githubusercontent.com/Bridgology/bridgology-releases/assets/map-dark.png#gh-dark-mode-only" alt="Map of concrete thickness over a curved bridge deck" width="900">
</p>

### Look inside the structure

Build C-scan volumes from grids of scans, slice them at any depth, pick the rebars automatically, and see the
layers in 3D.

## Works with your radar

| Manufacturer | Files |
|---|---|
| Proceq / Screening Eagle (GP8000, GP8100, GP8800, GS8000, GS9000) | `.sgy` |
| GSSI | `.dzt` (with `.dzx` for 3D grids) |
| MALÅ | `.rad` with `.rd3` / `.rd7` |
| IDS | `.dt`, C-thrue survey folders |
| Kontur | `.sgy` |
| Drone radars (SPH SkyHub, UTSI) | `.sgy`, `.LOG` |

## Install

**macOS**

1. Click **Download for macOS** above.
2. Open the downloaded file and drag **Bridgology** onto the **Applications** folder.
3. Start Bridgology from your Applications folder.

**Windows**

1. Click **Download for Windows** above.
2. Open the downloaded file and follow the steps. No administrator rights are needed.
3. Start Bridgology from the Start menu.

**Linux**

1. On Ubuntu or Debian, click **Download for Linux** above and install the file with your software
   centre, or with `sudo apt install ./Bridgology-*-linux-x64.deb`. Start Bridgology from your applications.
2. On another distribution, click **Download AppImage**, make the file executable
   (`chmod +x Bridgology-*-linux-x64.AppImage`) and open it.

Bridgology is signed by Bridgology SA, and the macOS version is checked by Apple; the Linux packages are not
signed. Once installed, it tells you when a new version is out and can install it for you (**Help > Check for
updates…**); on Linux it opens the download page.

## Free Viewer, or the full analysis with a licence

Bridgology is free to download and install. Without a licence key it runs as the **Viewer**, with no time
limit. A licence key turns the same installation into the full analysis software: nothing to reinstall.

| | Free Viewer | With a licence |
|---|:---:|:---:|
| Import radar files from every supported system and save them as a project | ✓ | ✓ |
| View, process and organise the radargrams | ✓ | ✓ |
| Place the scans on the site plan | ✓ | ✓ |
| Build and view C-scan volumes (depth slices) | ✓ | ✓ |
| Open a project delivered to you and read, adjust and export its maps | ✓ | ✓ |
| Describe the structure and pick layers, rebars and other features | | ✓ |
| Calculate thicknesses, depths, spacings and material properties | | ✓ |
| Make your own maps and export results to Excel | | ✓ |

The Viewer is the way to look at a survey Bridgology delivered to you, or to try the software on your own
data before you buy.

To get a licence, write to [info@bridgology.com](mailto:info@bridgology.com) or visit
[www.bridgology.com](https://www.bridgology.com). Enter the key in **Help > Licence key…**.

## System requirements

- A Mac with Apple Silicon (M1 or later), a PC with Windows 10 or 11 (64-bit), or a 64-bit PC with Ubuntu
  22.04 or later (or another Linux as recent, with the AppImage)
- An internet connection when the app starts, to check the licence

## Help

The full manual is built into the app: **Help > Help**. For anything else, use **Help > Contact support…**,
write to [info@bridgology.com](mailto:info@bridgology.com), or visit
[www.bridgology.com](https://www.bridgology.com).

<br>

<p align="center">
  <sub>© 2026 Bridgology SA</sub>
</p>
