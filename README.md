# Repro for macOS

**A little less explaining.** Record an issue, capture a screenshot, and drag it into your conversation or ticket.

[Download the latest Repro release](https://github.com/kubaklatt/repro-releases/releases/latest)

## Install once

1. Download the ZIP from the latest release and extract it.
2. Move **Repro.app** to a permanent location, ideally Applications, and open it.
3. Choose a window, display, or area. Record a video or use the camera button for a PNG screenshot.
4. Grant screen capture access if macOS requests it.

Requires **macOS 15.2 or later**. The app supports Apple Silicon and Intel.

This is a noncommercial community build, signed locally but not notarized by Apple. macOS or a managed device policy may block the first launch. Follow your organization's policy. No Apple notarization is claimed.

## Updates

Starting with **0.4.0**, Repro checks for updates automatically and can download them in the background. Choose **Repro → Check for updates…**, or use the Updates section in Settings. Install on quit or restart when ready; capture is protected during installation.

Versions **0.3 and earlier need this one manual upgrade** to obtain the updater.

Updates use Sparkle and require valid Ed25519 signatures on the download and release feed. The signing key stays with the maintainer. Downloads are public; the development repository is private.

## Your data

Videos and screenshots stay on your Mac. There are no accounts, cloud uploads, or tracking features. The updater contacts GitHub to check for and download releases; your captures are never sent.

## Useful shortcuts

| Action | Default |
|---|---|
| Start / stop recording | Control + Option + Command + R |
| Save and start next | Control + Option + Command + N |
| Retake | Control + Option + Command + Return |
| Screenshot | Control + Option + Command + S |

Shortcuts can be changed in Settings. Repro currently captures video without audio.

This repository distributes application releases and their signed update feed. It does not contain the application's source code.
