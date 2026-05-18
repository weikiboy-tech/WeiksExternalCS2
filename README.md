<p align="center">
  <h1 align="center">WeikExternalCs2</h1>
  <p align="center">Private Windows CS2 overlay with license-gated access, modern UI controls, and owner-managed distribution.</p>
</p>

---

## Overview

WeikExternalCs2 is a private desktop overlay client for CS2 focused on usability, clean visuals, and controlled access.

This repository is a public information page only. It does not contain source code, signing material, internal tooling, customer keys, or private build assets.

## Project Status

| Area | Status |
| --- | --- |
| Product | Private build |
| Access | Signed license required |
| Source code | Private |
| Release flow | Owner controlled |
| License generator | Private |

## Feature Overview

### Rage
- Aim assist controls
- Adjustable FOV and smoothing
- Bone selection
- RCS controls
- Keybind configuration

### Visuals
- ESP box and corner box variants
- Health, name, weapon, and flag rendering
- Bomb carrier indicator
- Skeleton ESP controls
- Advanced box style editor
- Ground item controls:
  - Ground weapons toggle
  - Ground grenades + Zeus toggle
  - Pistol exclusion for ground rendering
  - Compact marker style for dropped items

### Radar
- Round overlay radar
- Adjustable radar size
- Adjustable radar radius
- Corner positioning
- In-UI guidance for ingame radar zoom alignment

### Misc / Config
- Triggerbot controls
- Adjustable trigger delay
- BunnyHop toggle
- Centralized keybind management
- Save / reload / reset defaults

## Interface and UX

The overlay uses a compact dark/gold design language with tab-based navigation and fast in-app tuning.

Highlights:
- Structured tabs for Rage, Visuals, Radar, Misc, and Config
- Live updates from UI controls
- Quick startup defaults and profile-style behavior
- Practical control density for ingame adjustments

## Screenshots

| Overlay Menu | Ingame Overlay |
| --- | --- |
| ![Overlay Menu](https://raw.githubusercontent.com/weikiboy-tech/WeiksExternalCS2/main/.github/ISSUE_TEMPLATE/Screenshot%202026-05-18%20213935.png) | ![Ingame Overlay](https://raw.githubusercontent.com/weikiboy-tech/WeiksExternalCS2/main/.github/ISSUE_TEMPLATE/Screenshot%202026-05-18%20214951.png) |

## License Activation

Access is controlled through signed offline license files.

1. Start the client.
2. If no valid license is present, the client shows a Machine ID.
3. Send the Machine ID to the owner.
4. Receive the signed license file.
5. Place `license.key` next to the application.
6. Start again with valid license.

## Security and Privacy Model

This public repository is intentionally limited to product information.

Never published here:
- application source code
- private signing key
- license generator
- customer license files (`license.key`, `*.key`)
- debug symbols (`.pdb`)
- internal build output

See [SECURITY.md](SECURITY.md) for more details.

## Community / Support

For access and support requests:
- Discord: [https://discord.gg/yNSr2Jycbh](https://discord.gg/yNSr2Jycbh)

## Repository Notice

This repository is not open source. It is a public-facing project page for WeikExternalCs2.

All rights reserved.
