<p align="center">
  <h1 align="center">WeikExternalCs2</h1>
  <p align="center">Private Windows overlay client with a polished dark/gold interface and owner-controlled license access.</p>
</p>

---

## Overview

WeikExternalCs2 is a private Windows desktop overlay client focused on a clean premium interface, fast configuration access, and controlled distribution through signed license keys.

This repository is the public product page only. It does not contain source code, internal tooling, private signing keys, customer license files, or build artifacts.

## Current Status

| Area | Status |
| --- | --- |
| Product | Private build |
| Access | License required |
| Releases | Owner controlled |
| Source code | Private |
| License generator | Private |
| Customer keys | Created manually |

## Interface

The client uses a custom dark/gold overlay style designed around compact controls, clear tab navigation, and fast in-app configuration.

Highlights:

- Premium dark/gold visual style
- Compact tab-based menu layout
- Live configuration controls
- Custom startup defaults
- Keybind support
- Save, reload, and reset workflow
- Signed startup license check
- Optional machine-bound access
- Optional time-limited access

## License Activation

Access is controlled with signed offline license files.

1. A user starts the client.
2. If no valid license is available, the client displays a Machine ID.
3. The user sends the Machine ID to the owner.
4. The owner creates a matching license file.
5. The user places the received `license.key` next to the application.
6. The client starts only when the license is valid.

Licenses can be created after release. They do not need to be generated before publishing a build.

## Distribution Model

The public repository is intentionally minimal. The build, private tools, and license generator stay outside this repository.

Kept private:

- application source code
- release binaries unless distributed manually by the owner
- license generator
- private signing key
- generated customer license files
- debug symbols
- internal build output
- customer Machine IDs

## Owner Notes

Recommended owner workflow:

1. Build the private client locally.
2. Keep the license generator private.
3. Distribute the client only through the chosen private release channel.
4. Let users send their Machine ID after first start.
5. Create licenses manually per user.
6. Prefer short license durations for better access control.

## Security

The public repository is designed to reveal as little as possible. It is a public presentation page, not an open-source repository.

Important rules:

- never publish the license generator
- never publish the private signing key
- never publish `license.key`
- never publish customer `.key` files
- never publish debug `.pdb` files
- never publish old test builds by accident
- never push internal source folders into this public repository

More details are listed in [SECURITY.md](SECURITY.md).

## Support

Access, renewal, and license questions are handled privately by the project owner.

## Repository Notice

This repository is not open source. It is provided as a public information page for WeikExternalCs2.

All rights reserved.
