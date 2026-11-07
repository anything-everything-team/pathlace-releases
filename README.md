# Pathlace downloads

This repository holds the installers for **Pathlace Studio** and the **Pathlace Player**. The source code lives in a private repository; this one exists so anyone can download the apps without a GitHub account.

Website and docs: https://pathlace.com

## Pathlace Studio

Grab the latest version from the [Releases page](https://github.com/anything-everything-team/pathlace-releases/releases/latest):

| Platform | File |
| --- | --- |
| macOS, Apple silicon | `Pathlace.Studio_x.y.z_aarch64.dmg` |
| macOS, Intel | `Pathlace.Studio_x.y.z_x64.dmg` |
| Windows | `Pathlace.Studio_x.y.z_x64-setup.exe` or the `.msi` |
| Linux | `.AppImage`, `.deb` or `.rpm` |

The apps are not code-signed yet. On macOS, right-click the app and choose Open the first time. On Windows, choose More info, then Run anyway on the SmartScreen prompt.

## Pathlace Player

The Player is the runtime that Studio wraps around a program when you export it as a runnable app (File, then Export, then Runnable app). You normally do not download it by hand; Studio and the `plc pack` command fetch the right one for the chosen platform from this repository.

## Browser edition

Try Pathlace without installing anything: https://pathlace.com/app/
