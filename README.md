# vista2xp --- Vista-to-XP application converter

## What's this?

This software may be able to convert an app for Vista/7/10 to an XP app.
I'm sorry if unable to do it.

Platforms: Vista/7/10

## How it works?

It modifies the IAT (Import Address Table) of EXE/DLL files.
Importing of `kernel32.dll` will be changed to `v2xker32.dll` I created.
File `v2xker32.dll` will do workaround for XP.

## How to use?

1. Open `vista2xp.exe` program file. A dialog box will be open.
2. Drop the EXE/DLL files to the dialog to be converted.
3. Click the `[Convert]` button.
4. Files will be converted. File `v2xker32.dll` will be automatically added if necessary.
5. If you want to revert, please use the files inside the `Vista2XP-Backup` folder that was created.

## Contact Us

Katayama Hirofumi MZ
katayama.hirofumi.mz@gmail.com
