**Changes**

_New_
- add 21:9 and 4:3 modes
- add option to show lock icon for encrypted PVR channels (show encrypted channel icons by default)

_Improved_
- use OSMC busy spinner for widget loading
- add Disabled option to Adjust OSD on-time during video pause button
- rework skin structure for Transiflex localization
- improve widget icon animations
- rework dialog animations to prevent bright transition
- add heading to right list of home menu customization dialog

_Fixed_
- don't show parts of weather widget during widget loading
- localize all labels
- adjust home menu customization dialog to match behaviour of other settings windows

**Changelog v18.1.0**

_rename languages folder for Transiflex localization_

strings.po:
- add new localizes for not yet localized labels (31150-31169)
- add new localizes for second video info dialog screen (31170, 31171)
- add new localize for skinshortcuts dialog (31172)
- add new localize for skin settings advanced section (31173)
- add new localize for new encrypted PVR channel setting (31174)

_move 16x9 folder contents to new xml folder and add new aspect ratio modes by moving all coordinates to seperate files_

DialogPVRChannelGuide.xml:
- add scrollbar to channel list

DialogPVRChannelsOSD.xml:
- add scrollbar to program list

DialogVideoInfo.xml:
- replace extended info button localizes

Includes.xml:
- rework dialog animations to prevent bright transition

Includes_Widgets.xml:
- add conditional visibility to first weather widget panel
- move updating indicator down

MyPVRChannels.xml:
- remove watched status overlay

MyPVRRecordings.xml:
- adjust watched/listened to indicators for new icon file dimensions

script-skinshortcuts.xml:
- change inital focus to left list
- add heading for right list
- change localize of change label and change layout buttons
- adjust buttons sizes
- remove label2 of select widget button

script-skinshortcuts-static.xml:
- replace old busy-small.gif with default OSMC busy.gif
- improve widget icon animations

SkinSettings.xml:
- add skin reload button to debug section
- add Disabled option to Adjust OSD on-time during video pause button
- add new encrypted PVR channel setting

Variables.xml:
- adjust StatusOverlay and StatusOverlayWide variables to show correct icon for in progress TV shows
- change 3DMode variable for consistency (naming as per Kodi wiki) and to show more specific 3D information (HSBS, HTAB, SBS, TAB)
- change PVRChannelIcon and PVRChannelIconDialogOSD variables for new encrypted PVR channel setting

Textures.xbt:
- repack content of media folder after fixing watched indicator icons

template.xml:
- move updating indicator up
- replace old busy-small.gif with default OSMC busy.gif
- improve widget icon animations

_add resources folder_

addon.xml:
- rework syntax
- bump version to 18.1.0
