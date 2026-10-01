# AppSqeez Desktop

AppSqeez Desktop is a desktop application for app store optimization work: researching keywords, tracking rankings and ratings, managing competitors, and preparing store listing assets.

This repository is used only for public desktop releases.

## Download

Get the latest installer from the Releases page:

https://github.com/Sqeez-Studio/appsqeez-desktop/releases/latest

Choose the installer for your operating system:

| Operating system | Installer |
| --- | --- |
| Windows | `.msi` |
| macOS | `.dmg` |
| Linux Debian/Ubuntu | `.deb` |

## Install

### Windows

1. Download the `.msi` file from the latest release.
2. Open the installer.
3. If Windows SmartScreen warns about the app, choose `More info` and continue only if the file came from this repository.

### macOS

1. Download the `.dmg` file from the latest release.
2. Open the disk image.
3. Drag AppSqeez into Applications if prompted.
4. If macOS blocks the app because it is not notarized yet, open `System Settings > Privacy & Security` and allow the app only if the file came from this repository.

### Linux

Download the `.deb` file from the latest release, then install it with your package manager:

```bash
sudo apt install ./appsqeez*.deb
```

If your shell does not expand the filename, replace `appsqeez*.deb` with the exact downloaded file name.

## Updates

AppSqeez Desktop checks this repository's latest GitHub Release when it starts.

When a newer version is available, the app shows:

- a desktop notification,
- an in-app update toast,
- an item in the app's Notifications screen.

Updates are not installed automatically. Download the new installer from the latest release and run it manually.

## Release Notes

Each release contains installer assets and a short version note. Open the Releases page to see all versions:

https://github.com/Sqeez-Studio/appsqeez-desktop/releases

## Security

Download AppSqeez only from this repository unless Sqeez Studio publishes another official channel.

This release repository may contain unsigned installers during early distribution. Operating systems can show warnings for unsigned desktop apps even when the file is legitimate. If the warning appears, verify that:

- the installer was downloaded from `Sqeez-Studio/appsqeez-desktop`,
- the version matches the latest GitHub Release,
- the filename extension matches your operating system.

## Support

For support, questions, or bug reports, use the contact channel provided by Sqeez Studio. If GitHub Issues are enabled in this repository, you can also open an issue here.

