# Occulii — Releases

Signed, notarized macOS builds of **Occulii**, a lightweight menu bar system monitor: CPU, GPU, memory, network, disk and sensors in one calm panel.

> This repository hosts **release binaries and notes only** — it does not contain source code.

## Download

Grab the latest `.dmg` from the [**Releases**](https://github.com/RRCummins/occulii/releases/latest) page, or from [themrhinos.com/occulii](https://themrhinos.com/occulii).

## Install

1. Download `Occulii-<version>.dmg`.
2. Open the DMG and drag **Occulii.app** into your **Applications** folder.
3. Launch it. Occulii lives in the menu bar (look for the eye), not the Dock.

The build is signed with an Apple **Developer ID** and **notarized by Apple**, so it launches without Gatekeeper warnings.

## Requirements

- macOS 15 Sequoia or later
- Apple Silicon (the binary is universal, but sensors and fans are only tested on Apple Silicon Macs)
- No additional runtime dependencies

## Verifying the signature (optional)

```sh
spctl --assess --type execute --verbose=2 /Applications/Occulii.app
# => accepted / source=Notarized Developer ID
```

## Release notes

See [`CHANGELOG.md`](CHANGELOG.md) for per-version notes.
