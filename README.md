# GAGARIN NMS

A free base editor for **No Man's Sky**. Build a base in the app, then load it in the game.

Download the latest version from [Releases](../../releases).

![A temple built in the app](screens/01_hram_snaruzhi.jpg)

## Screenshots

Everything below was built and captured in the app.

| | |
|---|---|
| ![Inside the temple](screens/02_hram_vnutri.jpg) | ![Corvette in space](screens/03_korvet_kosmos.jpg) |
| Inside the same build | Corvette against the Milky Way |
| ![Corvette interior](screens/04_korvet_vnutri.jpg) | ![Station interior](screens/05_stanciya_vnutri.jpg) |
| Corvette interior | Station interior |
| ![Platform](screens/06_platforma.jpg) | ![Base at night](screens/07_baza_nochyu.jpg) |
| Living platform | The same base at night |
| ![Parts panel](screens/08_panel_detaley.jpg) | ![Save Manager](screens/09_save_manager.jpg) |
| Parts panel with 1,549 in-game parts | Bases read from the game save |

## Features

- **Parts catalog:** 1,549 in-game parts with their models, icons, and names in 17 languages, plus search, groups, and favourites.
- **Building tools:** snapping, move/rotate/scale controls, free placement, mirroring, curved placement, and reusable multi-part prefabs.
- **Painting:** in-game colours and finishes, with an eyedropper to copy paint from a placed part.
- **Save editing:** read bases from a No Man's Sky save and write them back.
- **Scene options:** panoramic backgrounds, ground coverings, time of day, lighting, and image settings.
- **Base tabs and session restore:** continue work after restarting the app.

## Install

1. Download `GAGARIN_NMS_v1.1.0.zip` from [Releases](../../releases).
2. Extract the archive with 7-Zip or Windows File Explorer.
3. Run `GAGARIN_NMS\\GAGARIN NMS.exe`.

There is no installer and the app does not write to the Windows registry. To uninstall it, delete the extracted folder.

**Requirements:** Windows 10 or 11 (64-bit), a DirectX 12 capable GPU, and about 7 GB of disk space (about 3 GB for the archive and 3.1 GB extracted).

### Automatic updates

Automatic updates are included starting with version 1.1.0. If you are using version 1.0.x, install version 1.1.0 manually once; later updates can be installed from inside the app.

### Windows warning on first launch

Windows may show “Windows protected your PC” because the app does not have a paid developer signature. Select **More info → Run anyway**. You can verify the download using the SHA-256 value in the release notes.

## No Man's Sky saves

The app can write a completed base directly to your game save. It blocks writes while the game is running, creates a dated backup before each write, and reads the file back to verify it afterward.

Please make your own copy of the save folder before your first edits.

Game saves are stored in:

```
%APPDATA%\\HelloGames\\NMS
```

The app's settings and tabs are stored in:

```
%LOCALAPPDATA%\\NMS_BuilderApp\\Saved
```

## Verify a download

The release notes include the SHA-256 checksum for the archive. In PowerShell, run:

```powershell
Get-FileHash 'GAGARIN_NMS_v1.1.0.zip' -Algorithm SHA256
```

The resulting hash must match the value in the release notes.

## Support

If something goes wrong, report what you did, what you expected, and what happened. Include your No Man's Sky version, GPU model, and the base file involved. Contact and support links are available in the app's main menu.

GAGARIN NMS is free and made by one person. Part models, icons, and names belong to Hello Games; the app displays assets already present in your copy of the game.
