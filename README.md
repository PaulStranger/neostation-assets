# NeoStation Themes Asset Repository

Welcome to the official **NeoStation** themes repository. Here you can find and contribute new visual styles to customize your gaming experience.

## Repository Structure

The structure is designed to be modular and easy to navigate for both humans and the application:

- `themes/`: Contains all individual theme folders.
- `preview/`: Global screenshots for the catalog display.
- `manifest.json`: Main index used by the app to list available themes.

## How to Create a Theme

### 1. Folder Setup
Create a new folder inside `themes/` with a descriptive name (e.g., `Matrix-Green`).

### 2. The `theme.json` File
Each theme must include a `theme.json` file with metadata and configuration:

```json
{
  "id": "my-unique-theme",
  "name": "Visual Name",
  "author": "Your Name",
  "version": "1.0",
  "description": "Short description of the style."
}
```

### 3. Assets
Inside your theme folder, create a `backgrounds/` subfolder for console background images.
- **Naming**: Files must be named as follows: `[shortname].[extension]` (e.g., `gba.png`, `nes.webp`, `ps1.jpg`).
- **Shortnames**: Use the official platform IDs (see list below).
- **Backup**: Always include a `default.png` for unspecified systems.

### Supported Systems (Shortnames)
Refer to these IDs when naming your background images:

`2600`, `32x`, `3do`, `3ds`, `5200`, `7800`, `8088`, `a2`, `a2001`, `all`, `amiga`, `android`, `arc`, `ard`, `ast`, `aw`, `bbcmicro`, `c64`, `cdi`, `chf`, `cpc`, `cps1`, `cps2`, `cps3`, `cv`, `dc`, `dos`, `ds`, `duck`, `fbneo`, `fc`, `fds`, `gb`, `gba`, `gbc`, `gc`, `genesis`, `gg`, `gw`, `intv`, `jag`, `jagcd`, `lynx`, `mame`, `mark3`, `md`, `mini`, `mo2`, `msx`, `music`, `n64`, `naomi`, `naomi2`, `naomigd`, `neogeo`, `nes`, `ngcd`, `ngp`, `ngpc`, `palm`, `pc98`, `pccd`, `pce`, `pcfx`, `pet`, `pico`, `pico8`, `plus4`, `ps1`, `ps2`, `ps3`, `psp`, `pspminis`, `rpgmaker`, `sat`, `satellaview`, `scd`, `scummvm`, `sfc`, `sg1k`, `sharpx68000`, `sms`, `snes`, `steam`, `switch`, `tg16`, `tgcd`, `tic80`, `uze`, `vb`, `vc4k`, `vect`, `vic20`, `vita`, `wasm4`, `wii`, `wiiu`, `ws`, `wsc`, `wsv`, `x1`, `xbox360`, `zx81`, `zxspectrum`.

## Rules and Recommendations

To keep the repository optimized and compatible:

- **Supported Formats**: 
  - `PNG` (recommended for logos/transparency)
  - `JPG` (photos)
  - `WebP` (optimized for fast loading)
  - `GIF` (supported for animated elements)
- **Resolution**: A square resolution of **1024x1024px** is recommended. This ensures compatibility and optimal performance across handheld or Android devices.
- **Optimization**: Run your images through tools like TinyPNG or similar before uploading.

## Publishing
Once your theme is ready, ensure you:
1. Add a screenshot to the `preview/` folder.
2. Register your theme in the `manifest.json` file at the root.
3. Open a Pull Request.

---
*Miguel Soto*
