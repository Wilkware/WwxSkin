# WwxSkin

[![Symcon](https://img.shields.io/badge/Symcon-WebFront--Skin-red.svg?style=flat-square)](https://www.symcon.de/service/dokumentation/entwicklerbereich/sdk-tools/sdk-skins/)
[![Product](https://img.shields.io/badge/Symcon%20Version-6.4-blue.svg?style=flat-square)](https://www.symcon.de/produkt/)
[![Version](https://img.shields.io/badge/Skin%20Version-1.6.20240703-orange.svg?style=flat-square)](https://github.com/Wilkware/WwxSkin)
[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-green.svg?style=flat-square)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

WebFront skin for Symcon

## Table of contents

1. [Features](#1-features)
2. [Size](#2-size)
3. [Compatibility](#3-compatibility)
4. [Installation](#4-installation)
5. [Changelog](#5-changelog)

### 1. Features

A complete documentation and explanation of the adjustments and extensions can be found at <https://wilkware.de/ip-symcon-skins/>.  
Here is a brief list of the adjustments:

* Fixed height of variable boxes, regardless of switches and actions.
* Slider width is limited to a maximum of 120 pixels, independent of the text length of the variable.
* Minimum button width is set to 29 pixels for a better grid layout with several buttons on top of each other.
* Own login logo (only if you use the skin as the default login skin).
* Notification messages are displayed with white text on an orange background.
* Dialogs are more central and transparent, i.e. they no longer cover the menu bar and are colored according to the skin (no longer simply black).
* The distances between the widgets on the right of the menu bar have been reduced.
* Scrollbars are displayed very narrow on PC (Google Chrome) so that the layout does not shift.
* Predefined table styles (Olive, Blue, Orange, Dark, Light and Lines) are included. In addition, there are simple predefined styles for left, right and center aligned columns.
* Color picker only via color box and not via the brush icon.
* Taller value selection dialog for more values without scrolling.

### 2. Size

* <40kB

### 3. Compatibility

This skin was developed and tested with the following versions:

* Symcon 6.x (all versions)
* Symcon 7.x (all versions)

Compatibility with versions prior to Symcon 6.0 should be given, but has not been tested!

### 4. Installation

See the Skin Control documentation (<https://www.symcon.de/service/dokumentation/modulreferenz/skin-control/>)  
or

1. Open the Symcon Management Console
2. Navigate to "Object tree > Logical tree view > Core instances > Skins" (DE: "Objektbaum > Logische Baumansicht > Kern Instanzen > Skins")
3. Click the "Add" button
4. Enter the following URL: <https://github.com/wilkware/WwxSkin>
5. Confirm with "OK"

### 5. Changelog

v1.6.20240703

* _NEW_: Brush icon for color selection hidden (color picker can only be activated via color box)
* _NEW_: Value selection dialog (own profiles) enlarged (taller) for more values without scrolling
* _NEW_: Table header colors extended (`light`, `dark` (turquoise) and `lines` in preparation for TileVisu v7)

v1.5.20211227

* _NEW_: Dialog (popup module) adjusted in size, position and transparency
* _NEW_: Widget styles optimized for available space
* _NEW_: Predefined styles for alignment of table columns (left, right and center)
* _FIX_: Update of the Wilkware login logo
* _FIX_: Alternating table cells

v1.4.20200205

* _NEW_: New notification message style (white/orange)
* _NEW_: Predefined table styles
* _FIX_: Scrollbar styles updated

v1.3.20190405

* _NEW_: Added Wilkware login logo

v1.2.20190404

* _NEW_: App-like scrollbars for Chrome browser (PC only)
* _NEW_: Added skin logo icon (WwxLogo)

v1.1.20190312

* _NEW_: Added minimum button width
* _FIX_: Increased maximum slider width from 100 to 120 pixels

v1.1.20190224

* _NEW_: Added maximum slider width

v1.0.20180116

* _NEW_: Initial version

## Developer

For more than 10 years now, I have been fascinated by the topic of home automation. In recent years, I have also been intensively involved in the Symcon community and contribute various scripts and modules there. You can find me there under the name @pitti ;-)

[![GitHub](https://img.shields.io/badge/GitHub-@wilkware-181717.svg?style=for-the-badge&logo=github)](https://wilkware.github.io/)

## Donations

The software is free for non-commercial use, I would appreciate a donation if you like the skin.

[![PayPal](https://img.shields.io/badge/PayPal-donate-00457C.svg?style=for-the-badge&logo=paypal)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=8816166)

## License

Attribution - NonCommercial - ShareAlike 4.0 International

[![License](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-EF9421.svg?style=for-the-badge&logo=creativecommons)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
