# Security Policy

## Public Repository Policy

This repository is documentation-only. It must not contain buildable source code, release binaries, customer data, license keys, private keys, or internal tools.

## Never Publish

- `tools/LicenseGenerator`
- private RSA keys
- `license.key`
- generated customer `.key` files
- `.exe`, `.dll`, `.pdb`, `.zip`, `.7z`, `.rar`
- `bin/`, `obj/`, `release/`, `.vs/`
- customer Machine IDs
- private config files
- internal screenshots containing customer data

## License Security

Licenses are signed offline. A valid offline license cannot be remotely revoked after it has been issued. For better control:

- issue short license durations
- bind licenses to a Machine ID
- keep the license generator offline
- rotate signing keys if a private key is exposed
- do not publish binaries in public GitHub releases

## If A Secret Leaks

1. Remove the leaked file from the repository immediately.
2. Assume the secret is compromised.
3. Generate a new signing key pair.
4. Update the private application build with the new public key.
5. Re-issue customer licenses.
6. Keep the old key blocked in future private builds.

## Reporting

Security issues should be reported privately to the project owner. Do not open public issues containing license keys, Machine IDs, private links, or bypass details.
