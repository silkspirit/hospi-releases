# Hospi for Windows

Public installer and automatic-update feed for the Hospi hotel concierge demonstration.

- [Download the latest Windows x64 installer](https://github.com/silkspirit/hospi-releases/releases/latest)
- [Open the Hospi web app](https://hospi-maison-alder.lovable.app/)
- [Release 0.1.0 installer](https://github.com/silkspirit/hospi-releases/releases/download/v0.1.0/Hospi-Setup-0.1.0.exe) · [SHA-256 checksums](https://github.com/silkspirit/hospi-releases/releases/download/v0.1.0/SHA256SUMS.txt)

This is an **unsigned Windows x64 demo**. Windows may show a trust prompt on installation. Install it for the kiosk's Windows user, then have an authorized staff operator sign in and activate the kiosk before guest check-in, service requests or voice sessions can begin. Activation and live voice depend on the hosted service being configured; downloading the installer does not provision them.

Hospi opens full-screen. Press **Ctrl+Shift+Q** for the operator exit confirmation. This demo does not lock down Windows itself.

Updates download automatically and restart Hospi only after the guest session has ended, pending work has finished, guest details have been cleared and the app has remained ready for thirty seconds. Installation and a two-version update still need verification on the target mini PC.

Maison Alder and its reservations are fictional. Identity checks, payments and physical keys are handled by staff. Use fictional guest information only.

The application source is private. This repository contains distribution documentation and release artifacts only; no provider or account credentials are included.
