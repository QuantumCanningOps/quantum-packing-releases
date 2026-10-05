# Quantum Packing releases

Desktop installers for Quantum Packing, and the `latest.json` manifest the app's
auto-updater reads.

Releases here are published by the `packing-desktop-release.yml` workflow in the
private source repository, on a `desktop-v*` tag. Each run creates a **draft**
release; publishing the draft is what ships it to installed apps.

Publish nothing else here. The updater reads this repository's latest release.
