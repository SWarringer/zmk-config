# ZMK config: Eyelash Sofle

My personal ZMK config for the Eyelash Sofle, with Swedish symbol and number layers. The OS layout must be set to Swedish.

![Eyelash Sofle Keymap](keymap-drawer/eyelash_sofle.svg)

- Keymap: `config/eyelash_sofle.keymap`
- Builds: GitHub Actions builds both the dongle and standalone (left central) firmware from `build.yaml`. To build locally, run `./build_local.sh build`.
- With the dongle, flash the dongle first, then the left half, then the right half, and power on the left half before the right.

## Underglow (RGB) controls

Hold **Sym + Num** together (left thumb + right thumb) to reach the **Light** layer.

| Left hand | Up (top row) | Down (home row) |
|---|---|---|
| Effect | Q | A |
| Hue | W | S |
| Saturation | E | D |
| Brightness | R | F |
| Speed | T | G |

- `1`: lights on/off
- Encoder: sweep hue
- Colour presets, right hand: Y U I O P = red, orange, yellow, green, cyan; H J K L Ö = blue, purple, magenta, pink, white

Effects are Solid, Breathe, Spectrum and Swirl (default). Hue and saturation only show in Solid and Breathe, so switch to Solid before using the presets or the encoder. Presets also set brightness to 60%. Settings persist across power cycles. The lights turn off when the keyboard is idle.

## Caps Lock

Double-tap either Shift to toggle Caps Lock. A single tap or hold is a normal Shift.
