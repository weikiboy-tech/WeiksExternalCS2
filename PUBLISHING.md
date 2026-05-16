# Publishing Guide

Use this folder as the public GitHub repository root.

Do not publish the main project root. The main project contains private implementation files, build artifacts, license tooling, and sensitive release history.

## Safe Public Upload

Upload only these files:

- `README.md`
- `SECURITY.md`
- `CHANGELOG.md`
- `PUBLISHING.md`
- `LICENSE`
- `.gitignore`
- `.gitattributes`
- `.github/ISSUE_TEMPLATE/config.yml`

## Recommended GitHub Settings

- Repository visibility: public only for this documentation folder
- Releases: disabled or unused
- Issues: disabled, or private contact only
- Wiki: disabled
- Discussions: disabled
- Actions: disabled unless needed for documentation

## Private Repository

Keep a separate private repository for internal development.

The private repository may contain source code, build scripts, and internal notes, but should still never contain customer license keys or generated customer `.key` files.

## Before Every Public Push

Check that the public repository does not contain:

- source folders
- build output
- ZIP releases
- executable files
- debug symbols
- license generator files
- private keys
- customer license files
