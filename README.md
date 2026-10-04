# GeometryCosmic Mixxx Skins

Two dark, CDJ-style skins for Mixxx DJ software, built around the Pioneer DDJ-400 FLX-4 mapping: a full-size skin and a compact one for 7" (1024x600) touch screens.

## Included Skins

### GeometryCosmic (full size)
- Big track display, jog wheel with cover art, hot cue pads, loop and beat-jump controls.
- Channel mixer with EQ, filter, VU meters and crossfader.
- Three Beat FX boxes, each with an effect selector, ON button, deck assign (1 / 2 / M), a META knob and a dry/wet knob.
- Full library view, samplers and intro/outro cues from the top bar.
- Color schemes: **Silverline** and **BlueOrange**.

![GeometryCosmic Preview](skin-setup.png)

### GeometryCosmic-7 (7" screens)
- Compact two-deck layout for 1024x600.
- A single wide Beat FX bar (the DDJ-400 drives one effect unit): 3 effect slots, each with an OFF button, META knob and selector, plus one dry/wet knob.
- A LIBRARY button in the top bar opens the full library.
- No color schemes.

![GeometryCosmic-7 Preview](geometry-cosmic-7.png)

## FX knobs
- **LEVEL/DEPTH**: moves the dry/wet knob.
- **SHIFT + LEVEL/DEPTH**: moves the META knob of the focused effect.

## Installation
Copy both `GeometryCosmic` and `GeometryCosmic-7` into your Mixxx skins folder:
- **Windows**: `C:\Users\<YourUsername>\AppData\Local\Mixxx\skins\`
- **Linux / Raspberry Pi**: `~/.mixxx/skins/`

### Installation via Terminal / SSH (Linux & Raspberry Pi)

To install or update both skins directly to your Mixxx directory, open your terminal (or SSH into your Pi) and run:

```bash
cd ~/.mixxx/skins && rm -rf GeometryCosmic GeometryCosmic-7 GeometryCosmic-Mixxx-Skins && git clone [https://github.com/djayza/GeometryCosmic-Mixxx-Skins.git](https://github.com/djayza/GeometryCosmic-Mixxx-Skins.git) temp_skins && cp -r temp_skins/GeometryCosmic temp_skins/GeometryCosmic-7 . && rm -rf temp_skins

Then in Mixxx go to **Options ➔ Preferences ➔ Interface** and pick the skin. Press `Ctrl + Shift + R` to reload a skin without restarting.

## Notes
- Tested with: Mixxx <version>, DDJ-400.
- Other controllers work, but the FX labels assume the DDJ-400 layout.

## License
<add your license, e.g. MIT or GPL-2.0>
