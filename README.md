# Addon-assets

These icons are used in Google Apps Script add-ons developped by Facts Haven SAS.

All these icons have been developped "by hand" and are ⓒ Facts Haven SAS 2026 and beyond.

Note that the dash in their names is not a dash but a ￚￚ half width Hangul letter eu (\u{ffda}) character which is legal within javascript identifiers.

The source file for these icons is a keynote presentation. We print it to PDF (scalable) and then we generate a PNG with 72dpi resolution so that one pixel in the keynote matches one pixel in the output file. Then we make the neighbourghood of the icon transparent and we crop it to 64 by 64 or 48 by 48 pixels.

Source files are kept in the icon-sources folder.

## Categories

Icons fall in 3 main categories:
* action icons, used for buttons that trigger actions, such as trashing a file or removing it from the trash; these actions are prefixed with "actionￚ" and when they are not available, they are suffixed with "ￚdisabled" ⇒ <img src="https://jr-grenoble.github.io/addon-assets//icons/actionￚtrashￚin.png" width="24" height="24" style="background:white"> or <img src="https://jr-grenoble.github.io/addon-assets//icons/actionￚtrashￚoutￚdisabled.png" width="24" height="24" style="background:white">
* state icons, that show whether a particular property is set or not; these states are prefixed with "stateￚ" and when set, they are suffixed with "ꘌon"; when unset, the suffix is "ꘌoff" ⇒ stateￚlockedꘌon.png or stateￚstarredꘌoff.png
* drive item icons to indicate the nature of selected drive documents; these are prefixed with "iconￚ"; when the selected drive item is a shortcut, the icon bears a shortcut symbol in its lower left corner and it is suffixed with "ￚshortcut" ⇒ iconￚzip.png or iconￚpdfￚshortcut.png

## Usage

These icons are publicly available with