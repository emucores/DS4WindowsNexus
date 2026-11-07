# DS4Windows Nexus v1

**Your controller. Your way.**

The first stable Nexus release for Windows 10 (build 19041+) and Windows 11, x64.
Version **1.0.1** includes the audio-source recovery fix validated during final testing.

## Downloads

- **DS4Windows-Nexus-x64.zip** — small main download. Requires Microsoft .NET 10 Desktop Runtime for Windows x64 already installed. Extract and run `DS4Windows.exe`.
- **DS4Windows-Nexus-x64-First-Run.zip** — the same app plus Microsoft's verified .NET 10.0.14 Desktop Runtime installer. Extract and run `First Run.cmd` once; Windows may request administrator approval.
- **DS4Windows-Nexus-Source.zip** — complete matching app source and build files. Use this asset for the GPL source; GitHub's automatic source archives may contain only the repository landing files.
- **SHA256SUMS.txt** — checksums for the three downloads.

Both app ZIPs extract into **DS4Windows Nexus x64** and contain one user README plus required license notices. Future updates can use the small main download.

## Features

### Controller workspace and profiles
- A redesigned Overview with battery, connection, input report rate, selected controller, active profile and useful controls.
- Clear descriptions on every tab, searchable settings and layouts that adapt to narrower windows.
- Button/stick mapping, dead zones, response curves, touchpad gestures, motion/gyro controls and special actions on supported devices.
- Per-game Auto Profiles, presets, Game Setup Wizard, profile comparison, history and backups.

### Feedback and audio
- DualSense and DualSense Edge Trigger Lab: linked or independent L2/R2 effects, feedback/weapon/vibration designs and optional full-pull actions.
- Audio Haptics from system audio or selected app sessions, with gain, left/right strength, balance and response controls.
- USB and Bluetooth audio haptics for DualSense and DualSense Edge.
- Controller speaker/headset streaming from a selected Windows output or app, configured separately from grip haptics.
- Lightbar colors, player indicators, rumble and temporary feedback previews.

### Setup, updates and support
- Latest stable Alia5 VIIPER lookup with download verification; USBIP installed when needed.
- Saved setup progress and automatic continuation after a required Windows restart.
- Verified HidHide and FakerInput installer downloads.
- GitHub stable-update checking and size/SHA-256 verified app downloads.
- Connection checks, searchable logs and optional support diagnostics.

## Fixes included

- Removed setup UI blocking and corrected VIIPER server startup/reconnect checks.
- Added reliable restart continuation and direct optional-driver installation.
- Corrected USB audio sample handling and Bluetooth haptics media delivery.
- Kept local lightbar changes on Bluetooth media frames, including DualSense Edge.
- Replaced the unavailable virtual speaker source with real Windows/app audio capture.
- Prevented an empty app-only source after automatic game following is turned off, and added Use System Audio recovery.
- Reduced testing clutter and separated speaker playback, grip haptics, trigger effects and their diagnostics.

## Requirements and compatibility

Windows x64, a supported controller, and Microsoft .NET 10 Desktop Runtime. Virtual output requires VIIPER/USBIP; setup guides installation. HidHide and FakerInput are optional.

Virtual controller output: **Xbox 360, DualShock 4, DualSense and DualSense Edge**. Xbox One/Series and Switch 2 virtual output are not included in this release. Native virtual audio/microphone endpoints and advanced native game-trigger passthrough are not included; local Audio Haptics and Trigger Lab control the physical device separately. Edge adaptive effects require the rear trigger stops in full-travel position.

## Validation and release status

213 automated checks passed and the Windows app/helper built successfully. The user confirmed driver setup/restart continuation, optional installers, rumble, adaptive triggers, audio, and the Edge Bluetooth lightbar during hardware testing. Hardware coverage does not imply every controller/game combination has been tested.

**This release is unsigned.** Windows may display an unknown-publisher or SmartScreen warning. Code signing will be added when a publisher certificate or signing service is available.

[Downloads and guides](https://ds4-windows.com/download/) · [Website](https://ds4-windows.com) · [Report an issue](https://github.com/emucores/DS4WindowsNexus/issues)
