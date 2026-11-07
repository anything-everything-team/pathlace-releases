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

The Player is the runtime that Studio wraps around a program when you export it as a runnable app (File, then Export, then Runnable app). You normally do not download it by hand; Studio and the `plc pack` command fetch the right one for the chosen platform from https://pathlace.com/dl/ or from this repository.

| File | What it is |
| --- | --- |
| `pathlace-player-windows-x64.exe` | Windows Player; your program is appended to it to make `YourGame.exe` |
| `pathlace-player-linux-x64` | Linux Player, same idea |
| `pathlace-player-macos-aarch64.app.zip`, `pathlace-player-macos-x64.app.zip` | macOS Player bundles; your program goes in `Contents/Resources/pathlace-program.json` |

Exported programs can also be plain `.html` files (File, then Export, then Save .html) that run in any browser with no download at all.

## Mirror

Every release is also mirrored at `https://pathlace.com/dl/<version>/` with a `SHA256SUMS.txt`, and `https://pathlace.com/dl/latest.json` names the current version.

## Browser edition

Try Pathlace without installing anything: https://pathlace.com/app/
