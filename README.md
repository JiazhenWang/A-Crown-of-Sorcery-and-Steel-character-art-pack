# A Crown of Sorcery and Steel - Portrait Overhaul

An unofficial portrait replacement mod for the Windows/Electron release of **A Crown of Sorcery and Steel**.

This mod replaces only the 14 character portrait images. It does not change the ChoiceScript text, chapter headers, UI icons, save data, or gameplay logic.

![New portrait contact sheet](media/new_portrait_contact_sheet.jpg)

## What It Replaces

The installer patches these portrait files inside `resources/app.asar`:

- `deploy/anattho.jpg`
- `deploy/cora.jpg`
- `deploy/devatta.jpg`
- `deploy/etrik.jpg`
- `deploy/grinn.jpg`
- `deploy/ibbahn.jpg`
- `deploy/khattya.jpg`
- `deploy/lazar.jpg`
- `deploy/nidana.jpg`
- `deploy/od.jpg`
- `deploy/okka.jpg`
- `deploy/rukir.jpg`
- `deploy/tika.jpg`
- `deploy/vid.jpg`


## Install

1. Download this repository as a ZIP from GitHub.
2. Extract the ZIP somewhere outside the game folder.
3. Double-click `install.bat`.
4. When prompted, confirm or paste the game folder path.

The game folder is the folder that contains:

```text
ACrownOfSorceryAndSteel.exe
resources\app.asar
```

The installer creates a backup before patching:

```text
portrait_overhaul_backup\app.asar.original
portrait_overhaul_backup\original_portraits\
portrait_overhaul_backup\original_portrait_contact_sheet.jpg
```

## Uninstall

Double-click `uninstall.bat` and point it at the same game folder.

The uninstaller restores:

```text
portrait_overhaul_backup\app.asar.original
```

If you manually want to restore the original version, copy `portrait_overhaul_backup\app.asar.original` back to:

```text
resources\app.asar
```

## Notes

- Windows only.
- No Python or Node.js install is required.
- The scripts do not connect to the internet.
- Save files should not be affected.
- If the game is updated or verified through a launcher, the launcher may overwrite the modded `app.asar`; run the installer again afterward.

## Credits And Disclaimer

See [CREDITS_AND_DISCLAIMER.md](CREDITS_AND_DISCLAIMER.md).
