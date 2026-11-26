# Diamond Radio ATS-25 USB PC Control 1.1.1

This maintenance release fixes USB connection and ATS Mini NAVTEX issues in the standalone offline Windows application.

## Fixed in 1.1.1

- **CONNECT works again:** the connection-page script error that could prevent the radio chooser from opening has been fixed.
- **Explicit radio selection:** every new PC Control or standalone FT8 connection lets you choose among connected ATS-25 and ATS Mini radios. A previously authorized Mini is not silently selected.
- **Independent radio tabs:** FT8/FT4/FT2 decodes, maps, callsign selection, and popup windows remain isolated to their owning radio tab.
- **ATS Mini NAVTEX restored:** NAVTEX now appears next to RTTY, and its decoder button opens the USB NAVTEX view instead of incorrectly falling back to PC-audio decoding.
- **Clearer busy-port guidance:** if the selected radio is already occupied, the console asks you to choose a different radio or close the other application.
- Added build-time checks for page JavaScript, explicit USB selection, per-tab FT8 channels, and ATS Mini NAVTEX availability.

No radio firmware update is required, and this release does not change the firmware protocol.

## Included features

- ATS-25 and ATS Mini USB control at 115200 baud.
- FM/HF tuning, modes, bandwidth, step, AGC, ATT, volume, mute, seek, and BFO.
- Live spectrum/waterfall, FT8/FT4/FT2 decodes, CW, RTTY, and NAVTEX text.
- NAVTEX presets, exact USB-dial tuning, TXT export, and an offline worldwide broadcast schedule.
- Optional PC-audio NAVTEX, SSTV, WEFAX, and PSK31 decoders.
- Favorites, bundled EiBi on-air schedules, local FT8 maps, country data, and flags.
- Simplified offline navigation with only PC Control and FT8 Map.

No Python installation, account, website access, or internet connection is required for USB control and local features. POTA and SOTA live spots require internet.

## Download and use

The **Windows ZIP** is recommended and includes the EXE, usage information, and legal notices. The **standalone EXE** contains the complete application and all local assets.

1. Connect the radio with a USB data cable and run the application.
2. Click **CONNECT** and select the desired ATS-25 or ATS Mini COM port.
3. On ATS-25, first enable **SETTINGS → PC CONNECTION**. ATS Mini needs no such setting.
4. For Mini NAVTEX, open **NAVTEX**, select a channel or enter the USB dial frequency, and use **TUNE NAVTEX**.

Keep the launcher open during use. Only one program or browser tab may hold a particular radio's COM port. On ATS Mini, use **DISCONNECT** before closing the console; the known final-browser-tab-close restart behavior is unchanged by this release.

The package passed JavaScript parsing, encryption round-trip, frozen-executable, local-server security/asset, native GUI, simulated multi-radio connection, Mini NAVTEX launch, and ZIP-integrity checks. Physical radio behavior remains subject to the connected hardware and firmware version.

Older releases remain available. This repository contains binary releases and notices only; Diamond-specific source code is not distributed.
