# Tactile Game Engine releases

Public installers and update metadata for Tactile Game Engine, published by its release pipeline. Source and support are private.

Each release carries the macOS (Apple silicon) and Windows x64 installers, their blockmaps, `latest.yml`, `latest-mac.yml`, `min-version.json` and `SHA256SUMS.txt`. An installed editor updates itself from the newest release.

## Installing

Download the `.dmg` (macOS) or the `.exe` (Windows) from the [latest release](../../releases/latest). The editor asks for a Tactile sign-in when it starts.

Until the installers are signed, each release's notes say what to expect:

- **macOS** refuses an unsigned app the first time it is opened. Allow it under System Settings → Privacy & Security → *Open Anyway*, then open it again. An unsigned editor cannot replace itself, so when it asks for an update, download the new `.dmg` from the latest release instead.
- **Windows** SmartScreen shows "Windows protected your PC": choose *More info* → *Run anyway*. Updates install from the editor.
