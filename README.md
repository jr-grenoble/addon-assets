# Addon-assets

These icons are used in Google Apps Script add-ons developped by Facts Haven SAS.

All these icons have been developped "by hand" and are ⓒ Facts Haven SAS 2026 and beyond.

Note that the dash in their names is not a dash but a ￚￚ half width Hangul letter eu (\u{ffda}) character which is legal within javascript identifiers.

The source file for these icons is a keynote presentation. We print it to PDF (scalable) and then we generate a PNG with 72dpi resolution so that one pixel in the keynote matches one pixel in the output file. Then we make the neighbourghood of the icon transparent and we crop it to 64 by 64 or 48 by 48 pixels.

Source files are kept in the icon-sources folder.

## Categories

Icons fall in 3 main categories:
* action icons, used for buttons that trigger actions, such as trashing a file or removing it from the trash; these actions are prefixed with "actionￚ" and when they are not available, they are suffixed with "ￚdisabled" ⇒ `actionￚtrashￚin.png` <img src="./icons/actionￚtrashￚin.png" width="14" height="14" style="background:white"> or `actionￚtrashￚoutￚdisabled.png` <img src="./icons/actionￚtrashￚoutￚdisabled.png" width="14" height="14" style="background:black">.
* state icons, that show whether a particular property is set or not; these states are prefixed with "stateￚ" and when set, they are suffixed with "ꘌon"; when unset, the suffix is "ꘌoff" ⇒ `stateￚlockedꘌon.png` <img src="./icons/stateￚlockedꘌon.png" width="14" height="14" style="background:white"> or `stateￚstarredꘌoff.png` <img src="./icons/stateￚstarredꘌoff.png" width="14" height="14" style="background:black"> .
* drive item icons to indicate the nature of selected drive documents; these are prefixed with "iconￚ"; when the selected drive item is a shortcut, the icon bears a shortcut symbol in its lower left corner and it is suffixed with "ￚshortcut" ⇒ `iconￚsheet.png` <img src="./icons/iconￚsheet.png" width="14" height="14"> or `iconￚpdfￚshortcut.png` <img src="./icons/iconￚpdfￚshortcut.png" width="14" height="14">.

## Usage

These icons are publicly available via the https://jr-grenoble.github.io/addon-assets/icons URL prefix. E.g. https://jr-grenoble.github.io/addon-assets/icons/actionￚsyncￚdisabled.png ⇒ <img src="./icons/actionￚsyncￚdisabled.png" width="14" height="14">.

State icons are always displayed using the BORDERLESS text button style.