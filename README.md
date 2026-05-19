<p align="center">
  <h1 align="center">WeiksExternalCS2</h1>
  <p align="center"><strong>Fully external CS2 overlay framework</strong> built around read-only memory access, clean UI, and owner-managed distribution.</p>
</p>

---

## Overview

**WeiksExternalCS2** is a private Windows CS2 overlay project focused on a fully external architecture.

The core idea is simple: the client is designed to stay external and operate through **read-only memory access**. It does **not** rely on memory writing, injection, DLL mapping, or internal hooks.

This repository is a public-facing project page only. It does not contain source code, signing material, internal tooling, customer keys, private build assets, or license-generation files.

## Why WeiksExternalCS2?

Many public CS2 bases are messy, unstable, hard to maintain, or mix external code with risky internal techniques.

WeiksExternalCS2 is built to present a cleaner private project structure:

- Fully external design
- Read-only memory access only
- No memory writing
- No DLL injection
- No DLL mapping
- No internal hooks
- Lightweight overlay-first approach
- Modern dark/gold UI
- Owner-controlled access and release flow

## Architecture Focus

| Area | Approach |
| --- | --- |
| Process interaction | External read-only access |
| Memory writes | Not used |
| Injection | Not used |
| Internal hooks | Not used |
| Rendering | External overlay |
| Distribution | Private / owner controlled |
| Access | Signed license required |
| Source code | Private |

## Project Status

| Area | Status |
| --- | --- |
| Product | Private build |
| Repository | Public information page |
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
- Clean layout for private builds and controlled releases

## Screenshots

| Overlay Settings | Ingame Overlay |
| --- | --- |
| ![Overlay Menu](https://raw.githubusercontent.com/weikiboy-tech/WeiksExternalCS2/main/.github/ISSUE_TEMPLATE/Screenshot%202026-05-18%20213935.png) | ![Ingame Overlay](https://raw.githubusercontent.com/weikiboy-tech/WeiksExternalCS2/main/.github/ISSUE_TEMPLATE/Screenshot%202026-05-18%20214951.png) |

## License Activation

Access is controlled through signed offline license files.

1. Start the client.
2. If no valid license is present, the client shows a Machine ID.
3. Send the Machine ID to the owner.
4. Receive the signed license file.
5. Place `license.key` next to the application.
6. Start again with a valid license.

## Security and Privacy Model

This public repository is intentionally limited to product information.

Never published here:

- Application source code
- Private signing key
- License generator
- Customer license files (`license.key`, `*.key`)
- Debug symbols (`.pdb`)
- Internal build output
- Private release assets

See [SECURITY.md](SECURITY.md) for more details.

## Community / Support

For access and support requests:

- Discord: [https://discord.gg/yNSr2Jycbh](https://discord.gg/yNSr2Jycbh)

## Repository Notice

This repository is not open source. It is a public-facing project page for WeiksExternalCS2.

All rights reserved.

---

### Short Description

Fully external CS2 overlay project using read-only memory access only. No memory writing, no injection, no internal hooks.
