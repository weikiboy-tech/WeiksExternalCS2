# WeiksExternalCS2

<div align="center">

## Fully external CS2 overlay project built around read-only memory access

![Fully External](https://img.shields.io/badge/Fully-External-blue?style=flat-square)
![Read Only Access](https://img.shields.io/badge/Read_Only-Access-brightgreen?style=flat-square)
![No Memory Write](https://img.shields.io/badge/No_Memory-Write-red?style=flat-square)
![Auto Offsets](https://img.shields.io/badge/Auto-Offsets-gold?style=flat-square)

**Fully external architecture • Read-only memory access • Automatic offset updates • Clean custom UI • Owner-managed distribution**

</div>

---

## Overview

**WeiksExternalCS2** is a private Windows CS2 overlay project focused on a clean, fully external architecture. The client is designed to remain completely external to the game process and relies on read-only memory access to gather game state information.

This project does **not** use memory writing, injection, DLL mapping, or internal hooks. It operates as a standalone overlay with independent rendering and provides a polished, owner-controlled experience.

**Important:** This public repository is a project information page only. It does not contain:
- Application source code
- Signing materials or private keys
- License generators
- Customer license files
- Build assets or debug symbols
- Internal offset update implementation

---

## What Makes It Different?

Many public CS2 external bases suffer from poor architecture, inconsistent maintenance, limited customization, and fragile offset handling. **WeiksExternalCS2** approaches this differently:

- **Fully External Architecture** – No injection, no hooks, no game process modification
- **Read-Only Process Interaction** – Memory access is strictly read-only
- **No Memory Writes** – Complete separation from game memory mutations
- **Fully Custom Visuals** – Tune overlay appearance to your own style instead of fixed presets
- **Automatic Offset Update System** – Reduces manual maintenance after CS2 updates
- **Modern UI Design** – Clean dark/gold interface with structured controls
- **Private Build Quality** – Professional-grade implementation with owner-controlled releases
- **Clean Public Presentation** – Project page focused on transparency, not hype

---

## Release Status & Version History

| Version | Type | Status | Features | Release Date |
|---------|------|--------|----------|--------------|
| **Test Build** | Test Release | Available | Core framework without Rage features | May 20, 2026 |
| **Full Version** | Private | Signed License Required | Complete feature set (Rage, Visuals, Radar, Misc) | Available on Discord |

### Current Test Release

A **public test build** is available without Rage (aim assistance) features. This test version allows you to:
- Experience the fully external architecture
- Test the Visual ESP system
- Try the Radar overlay
- Evaluate the configuration UI and keybind system
- Assess overall stability and performance

**To access the complete version with all features**, join our [Discord community](https://discord.gg/6VGcTJr48s) and contact the owner for a signed license.

See [Releases](https://github.com/weikiboy-tech/WeiksExternalCS2/releases) for the latest test build downloads.

---

## Architecture Focus

| Component | Implementation |
|-----------|-----------------|
| **Process Interaction** | External read-only access |
| **Memory Writes** | Not used |
| **Injection** | Not used |
| **DLL Mapping** | Not used |
| **Internal Hooks** | Not used |
| **Rendering** | External overlay |
| **Offset Handling** | Automatic offset update system |
| **Configuration** | Save, reload, reset, and tune settings in UI |
| **Distribution** | Private / owner controlled |
| **Access** | Signed license required for full version |
| **Source Code** | Private |

---

## Project Status

| Aspect | Status |
|--------|--------|
| **Product** | Private build with public test release |
| **Repository** | Public information page |
| **Access** | Test build available; signed license required for full version |
| **Source Code** | Private |
| **Release Flow** | Owner controlled |
| **License Generator** | Private |
| **Offset Updater** | Included in private build |

---

## Features

### Fully External Core

The foundation of WeiksExternalCS2 is built on a fully external model:

- **Read-only memory access** – Access game state without modifications
- **External overlay rendering** – Visuals drawn independently from game process
- **No game-memory writes** – Complete protection against memory corruption
- **No internal code execution** – Client never executes within game context
- **No DLL injection or mapping** – Lightweight standalone structure
- **Clean process separation** – Overlay and game operate as isolated entities

### Auto Offset Update

CS2 updates regularly change memory offsets, and outdated overlay projects often break after patches. WeiksExternalCS2 includes an **automatic offset update system** designed to reduce manual maintenance.

- **Automatic offset refresh workflow** – Reduces downtime after game updates
- **Less manual maintenance** – Private build receives offset updates without user intervention
- **Cleaner update process** – Centralized offset handling minimizes disruption
- **Easier long-term maintenance** – Sustainable approach to evolving game memory

### Rage

Aim assistance features with full configurability (Full version only):

- Aim assist controls
- Adjustable FOV and smoothing
- Bone selection
- RCS (recoil control) settings
- Keybind configuration
- UI-based tuning for fast in-game adjustments

### Visuals

Fully custom visual settings allow you to tune the overlay to your own style:

- **Fully custom visual settings** – No locked presets; customize every element
- **ESP variants** – Box ESP and corner box options
- **Custom box styling** – Control box appearance and rendering style
- **Entity information** – Health, name, weapon, and flag display
- **Bomb carrier indicator** – Highlight bomb position
- **Skeleton ESP** – Adjustable bone visualization
- **Display controls** – Fine-tune visibility of each ESP element
- **Advanced box editor** – Precision control over visual appearance
- **Clean information layout** – Readable in-game overlay design
- **Ground item controls**:
  - Ground weapons toggle
  - Ground grenades and Zeus toggle
  - Pistol exclusion for filtered rendering
  - Compact marker style for dropped items

### Radar

Overview-focused radar with flexible positioning:

- Round overlay radar
- Adjustable radar size and radius
- Corner positioning options
- In-UI guidance for aligning in-game radar zoom
- Clean, minimalist design for quick reference

### Misc / Config

Utility and configuration features:

- Triggerbot controls with adjustable delay
- BunnyHop toggle
- Centralized keybind management
- Save, reload, and reset defaults
- Fast profile-style behavior for daily use
- Quick startup defaults

---

## Interface and UX

WeiksExternalCS2 features a polished, professional interface:

- **Compact dark/gold design language** – Modern, clean aesthetic
- **Structured tabs** – Rage, Visuals, Radar, Misc, and Config sections
- **Live UI updates** – Settings apply immediately during gameplay
- **Frequently accessed controls** – Quick access to common adjustments
- **Clean setting groups** – Organized menus instead of cluttered layouts
- **Practical control density** – Efficient space usage for in-game adjustments
- **Quick startup defaults** – Ready-to-use configuration on launch
- **Polished presentation** – Professional-grade private build quality

---

## Screenshots

### Overlay Settings UI
![Overlay Settings](.github/ISSUE_TEMPLATE/Screenshot%202026-05-18%20213935.png)

### Ingame Overlay
![Ingame Overlay](.github/ISSUE_TEMPLATE/Screenshot%202026-05-18%20214951.png)

---

## License Activation

WeiksExternalCS2 uses an offline signed license system:

1. **Start the client**
   - Application checks for valid license on launch

2. **If no license exists**
   - Client displays your Machine ID

3. **Send Machine ID to owner**
   - Provide the displayed Machine ID to the project maintainer in [Discord](https://discord.gg/6VGcTJr48s)

4. **Receive signed license**
   - Owner generates and sends a signed license file

5. **Place license file**
   - Place `license.key` next to the application executable

6. **Start again**
   - Launch client with valid license in place

---

## Security and Privacy Model

This public repository intentionally contains only product information and does not publish:

- Application source code
- Private signing keys
- License generator tools
- Customer license files
- Debug symbols or build artifacts
- Internal implementation details
- Private release assets
- Offset update mechanisms

All distribution, signing, and licensing is controlled privately by the owner.

---

## Support & Community

**Join our Discord for:**
- License activation support
- Test build feedback
- Feature showcase
- Community updates
- Direct support from the owner

👉 **[Discord Community](https://discord.gg/6VGcTJr48s)**

---

## Repository Notice

**This repository is not open source.** It is a public-facing project information page for WeiksExternalCS2.

All rights reserved.

---

<div align="center">

**Fully external CS2 overlay project using read-only memory access, fully custom visuals, and automatic offset updates. No memory writing, no injection, no internal hooks.**

</div>
