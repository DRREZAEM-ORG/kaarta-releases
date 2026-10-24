# Kaarta releases

Installers and update feeds for the Kaarta desktop app. The app's source is not here.

- **Download:** the latest macOS (Intel) installer is always at
  [releases/latest/download/Kaarta-macos-x86_64.dmg](https://github.com/DRREZAEM-ORG/kaarta-releases/releases/latest/download/Kaarta-macos-x86_64.dmg).
- **Update feeds** (read by installed copies, on the `gh-pages` branch): one per platform,
  `stable/<os>/<arch>/appcast.xml`, with `latest.json` beside it.

Everything here is published by Kaarta's release workflow. Nothing is edited by hand: releases,
their files and the feeds are regenerated from the release records, and an installed copy
accepts an update only if it is signed with Kaarta's update key.
