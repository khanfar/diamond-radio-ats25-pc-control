# Diamond Radio ATS-25 USB PC Control 1.1.0

This release brings the expanded Diamond PC Control interface to the standalone offline Windows application, including NAVTEX and additional PC-audio decoders.

## New in 1.1.0

- **NAVTEX over radio USB:** channel presets, exact USB-dial tuning, continuous green-box messages, and TXT export. No audio cable is required.
- **Offline NAVTEX schedule:** worldwide station timetable, scheduled-now and next-nearest filters, frequency filtering, QTH distance sorting, and one-click tuning.
- **PC Audio Decoder:** NAVTEX, SSTV, WEFAX, and PSK31 through a selected computer audio input.
- Improved live spectrum/waterfall presentation and decoder workspace.
- NAVTEX, CW, and RTTY messages continue beyond the initial visible area instead of stopping at the first screen of text.
- The NAVTEX timetable and all other required local assets are bundled and checked by the application's smoke tests.

## Existing features retained

- Complete ATS-25 USB receiver console with FM/HF tuning, modes, bandwidth, step, AGC, ATT, volume, mute, seek, and BFO.
- Live spectrum/waterfall and radio-side 3D waterfall control.
- FT8/FT4/FT2 presets and decodes.
- Favorite stations and the bundled EiBi schedule.
- Offline FT8 world map, country data, country flags, and map styles.
- Chrome or Edge app-mode launcher with a clickable local address.
- Simplified navigation showing only PC Control and FT8 Map.

No Python installation, account, website, or internet connection is required for USB control and local features. POTA and SOTA live spots require internet.

## Download and use

The **Windows ZIP** is recommended and includes the EXE, read-me, and legal notices. The **standalone EXE** contains the complete application and all local assets.

Connect the radio by USB, run the application, click **CONNECT** in the console, and select its COM port. For NAVTEX, open **NAVTEX**, choose a preset or enter the USB dial frequency, and click **TUNE NAVTEX**. Use **SAVE LOG** for TXT export and **NAV SCHED** for broadcast times. Keep the launcher open during use. Only one program or browser page can hold the COM port at a time.

The package passed frozen-executable self-tests, encrypted-page and bundled-asset checks, local HTTP security and asset tests, native GUI checks, and ZIP-integrity verification. Older releases remain available. This repository contains binary releases and notices only; Diamond-specific source code is not distributed.
