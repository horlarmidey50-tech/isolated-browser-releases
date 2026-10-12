# Isolated Browser — releases

Windows installers for **Isolated Browser**, a privacy-focused browser that keeps each browsing profile fully separate (its own cookies, storage and settings) and can sync your profiles between your own devices with end-to-end encryption.

## Download

Get the latest installer from this repository's **[Releases](../../releases/latest)** page (`IsolatedBrowser-Setup.exe`).

## Security

- Every release is signed with the project's release key (Ed25519).
- The app checks each in-app update against that signature and its SHA-256 before installing it, and refuses anything that doesn't match.
