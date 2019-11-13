**Changes**

_New_
- add new pre-defined widgets
- add setting to hide media flags

_Improved_
- rework home menu customization dialogs
- improve sort by and sort order toggles
- improve video info dialog (animations and buttons)
- improve aligment and positioning of item count and media flags

_Fixed_
- move hide scrollbars setting to skin settings window
- hide MyOSMC home menu entry and widget on non-OSMC systems

**Changelog v18.2.0**

_add new skin playlists and update existing ones_

strings.po:
- change localize for new hide scrollbars option (31005)
- add new localizes for new widget sort by, widget sort direction and widget limit options (31175, 31176, 31177)
- add new localizes for new pre-defined widgets and reworked home menu customization dialogs (31178-31232)
- add new localizes for improved sort by and sort order toggles (31233, 31234)
- add new localizes for additional widgets per script (31235, 31236)
- add new localize hide media flags setting (31237)

AddonBrowser.xml:
- remove deprecated view toggle
- remove hide scrollbar toggle
- fix side-menu coordinates
- add new "Sort order" localize to sort order toggle

Coordinates_Includes.xml:
- add SideMenuControlsSpacer_coords13 include for only one item in side/context menu
- change positioning of media flags (aligned with item count)

DialogFavourites.xml:
- change conditional onleft of scrollbar (submenu is only present during playback with active side-menu controls)
- change conditional visibility of submenu indicator (submenu is only present during playback with active side-menu controls)
- remove hide scrollbar toggle

DialogVideoInfo.xml:
- add fade animation to togglable dialog elemtents (plot, cast, extended info)
- show all buttons all the time
- improve extended info button to keep focus

EventLog.xml:
- add new "Sort order" localize to sort order toggle

Includes.xml:
- add black background layer behind background video playback to WindowBackgroundImage include
- add 13th spacer to SideMenuControlsSpacer include for only one item in side/context menu
- fix alignment of item count and media flags
- add new hide media flags functionality
- change seperator of duration/size label

MyGames.xml:
- add new "View: " localize to view toggle
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle

MyMusicNav.xml:
- add new "View: " localize to view toggle
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle

MyPics.xml:
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle

MyPlaylist.xml:
- fix side-menu coordinates
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle

MyPrograms.xml:
- add new "View: " localize to view toggle
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle

MyPVRChannels.xml:
- fix side-menu coordinates
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle

MyPVRGuide.xml:
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle

MyPVRRecordings.xml:
- fix side-menu coordinates
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle

MyPVRSearch.xml:
- fix side-menu coordinates
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle

MyPVRTimers.xml:
- fix side-menu coordinates
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle

MyVideoNav.xml:
- add new "View: " localize to view toggle
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle

script-skinshortcuts-static.xml:
- add conditional visibility to MyOSMC home menu entry
- point default movies and TV show widgets to new skin playlists
- change content lines to point to new skin playlists

script-skinshortcuts.xml:
- add new widget sort by, widget sort direction and widget limit options

SkinSettings.xml:
- add hide scrollbars setting formerly found in other windows
- add new hide media flags setting

Variables.xml:
- add new WidgetSortByLabel, WidgetSortDirectionLabel and WidgetLimitLabel variables for new widget sort by, widget sort direction and widget limit options
- improve duration variable

Textures.xbt:
- update textures file with new, bigger OSMC logo file
- update textures file with improved media flags icons

mainmenu.DATA.xml:
- add conditional visibility to MyOSMC home menu entry

overrides.xml:
- add general and widget groupings to sort user dialogs for home menu entries and widgets in home menu customization dialog
- point default movies and TV show widgets to new skin playlists
- change default music widget group to circumvent v18 skinshortcuts bug (missing/wrong localize for "music")
- remove unused "square" widget icon layout
- add new widget sort by, widget sort direction and widget limit properties

template.xml:
- add new widget sort by, widget sort direction and widget limit properties
- change content line for new widget sort by, widget sort direction and widget limit properties

addon.xml:
- bump version to 18.2.0
