# DS4Windows Nexus

**Your controller. Your way.**

DS4Windows Nexus v1 is an open-source Windows controller companion maintained by EmuCores. Customize mappings and profiles, tune supported controller feedback, and present a virtual controller your games understand.

[Website](https://ds4-windows.com) · [Download](https://ds4-windows.com/download/) · [Latest GitHub release](https://github.com/emucores/DS4WindowsNexus/releases/latest) · [Report an issue](https://github.com/emucores/DS4WindowsNexus/issues)

## Download Nexus v1

- [Small Windows x64 app](https://github.com/emucores/DS4WindowsNexus/releases/download/v1.0.1/DS4Windows-Nexus-x64.zip) — .NET 10 Desktop Runtime must already be installed.
- [First-run bundle](https://github.com/emucores/DS4WindowsNexus/releases/download/v1.0.1/DS4Windows-Nexus-x64-First-Run.zip) — includes Microsoft's runtime installer; run **First Run.cmd** once.
- [Matching source](https://github.com/emucores/DS4WindowsNexus/releases/download/v1.0.1/DS4Windows-Nexus-Source.zip) — complete GPL app source and build scripts.
- [SHA-256 checksums](https://github.com/emucores/DS4WindowsNexus/releases/download/v1.0.1/SHA256SUMS.txt).

Extract the complete **DS4Windows Nexus x64** folder, then run **DS4Windows.exe**. Existing profiles and verified drivers are reused. This release is currently unsigned.

## Features

- Controller Overview with live connection, battery, profile and feedback controls.
- Remapping, stick curves, dead zones, touchpad gestures, motion/gyro controls and special actions on supported devices.
- Auto Profiles, presets, guided game setup, profile history and backups.
- DualSense/Edge adaptive effects in Trigger Lab and Audio Haptics from system/app audio over USB or Bluetooth.
- Controller speaker/headset streaming, rumble and lightbar customization.
- Guided VIIPER/USBIP setup with saved restart continuation and optional HidHide/FakerInput installs.
- GitHub update checking, verified downloads, searchable settings and support diagnostics.

## Compatibility

Windows 10 build 19041+ or Windows 11, x64. Microsoft .NET 10 Desktop Runtime is required; the first-run bundle includes its official installer.

Virtual output: Xbox 360, DualShock 4, DualSense and DualSense Edge. Native virtual audio/microphone endpoints and advanced game-trigger passthrough are not included. Local Audio Haptics and Trigger Lab drive the physical controller separately. Feature availability depends on hardware, transport and game support. Edge adaptive effects require full trigger travel.

## Source and licenses

Download the **DS4Windows-Nexus-Source.zip** release asset for the full source corresponding to the distributed executables. GitHub's automatic source archives may contain only the repository landing files. Original DS4Windows and dependency licenses/notices are preserved in the app and source distributions.

See [What's New](RELEASE-NOTES.md) for the full v1 changes and validation scope. Lead developer: **EmuCores**.
