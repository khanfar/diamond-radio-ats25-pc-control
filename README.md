# Diamond Radio ATS-25 USB PC Control

Official standalone offline Windows PC Control application for **Diamond Radio ATS-25-family radios**.

- Product and Diamond-specific modifications: **M Khanfar**
- Distribution: **freeware**; Diamond-specific source code is not distributed
- Official website: **[diamondradio.web.app/pc-control.html](https://diamondradio.web.app/pc-control.html)**
- Current version: **1.0.0**

## Download

Open **[Releases](https://github.com/khanfar/diamond-radio-ats25-pc-control/releases/latest)** and choose:

- **DiamondRadio-ATS25Control-v1.0.0-Windows.zip** — recommended package with the EXE, usage information, and legal notices.
- **DiamondRadio-ATS25Control.exe** — standalone Windows application.
- **DiamondRadio-ATS25Control-v1.0.0-Licenses.zip** — complete legal notices.
- **SHA256SUMS.txt** — hashes for checking the release downloads.

No Python installation, account, website access, or internet connection is needed for USB receiver control. The interface, FT8 map, country flags, country data, and EiBi schedule are embedded in the EXE.

## Included features

- FM/HF tuning, modes, bandwidth, tuning step, AGC, ATT, volume, mute, seek, and BFO.
- Live spectrum/waterfall and the radio-side 3D waterfall control.
- FT8/FT4/FT2 presets and decode displays.
- CW and RTTY text displays.
- Favorite stations with TXT save/load.
- Bundled EiBi on-air schedule.
- Local FT8 world map with station information, country flags, and map styles.
- A simplified offline interface containing only PC Control and FT8 Map navigation.

**POTA and SOTA spot tabs are online-only services.** Internet availability does not affect USB receiver control, local decodes, favorites, EiBi, or the FT8 map.

## Quick start

1. Connect the ATS-25 to the PC using a USB data cable.
2. Run `DiamondRadio-ATS25Control.exe`.
3. The console opens in Chrome or Edge app mode.
4. Click **CONNECT** in the console and select the radio's COM port.
5. Use **PC Control** for the receiver console or **FT8 Map** for the standalone map page.

Keep the launcher open while using the console. Closing the launcher stops the local service. Only one application or browser page may hold the radio's COM port at a time; close other radio-control tools if the port is busy.

The local address `http://127.0.0.1:8789/pc-control.html` is clickable in the launcher. Website and companion-project links are also provided there.

## Companion projects

- [Diamond Radio ATS-25 Offline Tool](https://github.com/khanfar/diamond-radio-ats25-offline-tool) — firmware installation, backup, restore, maintenance, and offline EiBi Manager.
- [Diamond Radio ATS Mini Offline Tool](https://github.com/khanfar/diamond-radio-ats-mini-offline-tool) — offline ATS Mini installation and maintenance.
- [Diamond Radio ATS Mini firmware](https://github.com/khanfar/diamond-radio-ats-mini) — binary firmware releases and update information.

## Community

- Telegram: https://t.me/+aftBqV_qRMlkZDVi
- Facebook: https://www.facebook.com/share/g/1EpCchUdzj/
- YouTube: https://www.youtube.com/@DiamondRadioOfficial

## Legal and third-party notices

Diamond-specific source code is private. The application is distributed as freeware. Third-party components and data retain their own licenses and copyright notices.

- [`DIAMOND_FREEWARE_NOTICE.txt`](DIAMOND_FREEWARE_NOTICE.txt)
- [`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md)
- [`legal/`](legal/) — accompanying license texts

The software is provided without warranty.
