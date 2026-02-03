# Addon-assets

These icons are used in Google Apps Script add-ons developped by Facts Haven SAS.

All these icons have been developped "by hand" and are ⓒ Facts Haven SAS 2026 and beyond. Some of these icons are inspired by [Google material icons](https://fonts.google.com/icons?).

Note that the dash in their names is not a dash but a `ￚ` half width Hangul letter eu (\u{ffda}) character which is legal within javascript identifiers.

The source file for these icons is a keynote presentation. We print it to PDF (scalable) and then we generate a PNG with 72dpi resolution so that one pixel in the keynote matches one pixel in the output file. Then we make the neighbourghood of the icon transparent and we crop it to 64 by 64 or 48 by 48 pixels.

Source files are kept in the icon-sources folder.

## Categories

Icons fall in 3 main categories:
* action icons, used for buttons that trigger actions, such as trashing a file or removing it from the trash; these actions are prefixed with "actionￚ" and when they are not available, they are suffixed with "ￚdisabled" ⇒ `actionￚtrashￚinￚdisabled.png` <img src="./icons/actionￚtrashￚinￚdisabled.png" width="16" height="16" style="background:black;padding:2pt; border: 1pt solid white; border-radius:16pt"> or `actionￚshowￚstack.png` <img src="./icons/actionￚshowￚstack.png" width="16" height="16" style="background:#c8e5fd;padding:2pt; border: 1pt solid #c8e5fd; border-radius:16pt">.
* state icons, that show whether a particular property is set or not; these states are prefixed with "stateￚ" and when set, they are suffixed with "ꘌon"; when unset, the suffix is "ꘌoff" ⇒ `stateￚlockedꘌon.png` <img src="./icons/stateￚlockedꘌon.png" width="16" height="16" style="background:white;padding:2pt"> or `stateￚstarredꘌoff.png` <img src="./icons/stateￚstarredꘌoff.png" width="16" height="16" style="background:black"> .
* drive item icons to indicate the nature of selected drive documents; these are prefixed with "iconￚ"; when the selected drive item is a shortcut, the icon bears a shortcut symbol in its lower left corner and it is suffixed with "ￚshortcut" ⇒ `iconￚsheet.png` <img src="./icons/iconￚsheet.png" width="16" height="16"> or `iconￚpdfￚshortcut.png` <img src="./icons/iconￚpdfￚshortcut.png" width="16" height="16">.

## Usage

These icons are publicly available via the https://jr-grenoble.github.io/addon-assets/icons URL prefix. E.g. https://jr-grenoble.github.io/addon-assets/icons/actionￚsyncￚdisabled.png ⇒ <img src="./icons/actionￚsyncￚdisabled.png" width="14" height="14">.

State icons are always displayed using the BORDERLESS text button style.

Action icons that open a new card or a new tab or overlay window are displayed using the FILLED_TONAL style.

Action icons that simply toggle a state or do not create a new UI element are displayed using the OUTLINED style.

Drive item icons are pure images and do not require a style.