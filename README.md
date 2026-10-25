# NuvahSlicer — Windows downloads

Windows application downloads for the Nuvah team. Application source is maintained in a separate private repository.

[Download the latest Windows installer](https://github.com/petergorrr/NuvahSlicer-downloads/releases/latest)

## First installation

Download the `NuvahSlicer-...-Windows-x64-Setup.exe` attachment from the latest release and install it. Python is included; you do not need to install Python separately.

Supported build target: Windows 10 version 1809 or newer / Windows 11, x64. Follow your company's device security policy: these internal builds do not include a publicly trusted Windows publisher certificate.

## Later updates

While NuvahSlicer is running and online, it checks for newer releases. Use **Help → Check for updates…** for a manual check. Save your work before choosing to install; the application downloads and verifies the update before running its installer.

Update packages are verified using the Ed25519 public key embedded in the application. The private signing key is not stored in this repository or in the application.

The `internal-feed-windows-x86_64` prerelease holds the updater's XML feed; install the `.exe` from a normal version release.
