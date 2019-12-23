**Changes**

_New_
- add new pre-defined widgets
- add setting to hide media flags
- add setting to change whether video info dialog shows details or plot first
- add setting to set a solid color instead of background images

_Improved_
- rework home menu customization dialogs
- improve sort by and sort order toggles
- improve video info dialog (animations and buttons)
- improve alignment and positioning of item count and media flags
- show view toggle only when more than one view is available
- improve info dialogs (more information/layout with video and addon info dialogs)
- update Artist Slideshow integration (v3 update)

_Fixed_
- move hide scrollbars setting to skin settings window
- hide MyOSMC home menu entry and widget on non-OSMC systems
- fix overlapping in views with big horizontal titles
- add scrollbar to music album info dialog (if details list is too long)

**Changelog v18.2.0**

_add new skin playlists and update existing ones_

strings.po:
- change localize for new hide scrollbars option (31005)
- add new localizes for new widget sort by, widget sort direction and widget limit options (31175, 31176, 31177)
- add new localizes for new pre-defined widgets and reworked home menu customization dialogs (31178-31232)
- add new localizes for improved sort by and sort order toggles (31233, 31234)
- add new localizes for additional widgets per script (31235, 31236)
- add new localize hide media flags setting (31237)
- add new localizes for Transifex translation (31238-31266)
- change localize for new movie info dialog setting (31170)

AddonBrowser.xml:
- remove deprecated view toggle
- remove hide scrollbar toggle
- fix side-menu coordinates
- add new "Sort order" localize to sort order toggle

Coordinates_DialogAddonInfo.xml:
- adjust hight of details list
- adjust position and hight of description textbox
- add coordinates for new info line (last used, last updated)

Coordinates_DialogMusicInfo.xml:
- adjust hight of details list
- adjust position and hight of plot textbox
- add coordinates for scrollbar

Coordinates_DialogVideoInfo.xml:
- adjust hight of details list
- adjust position and hight of plot textbox

Coordinates_Includes.xml:
- add SideMenuControlsSpacer_coords13 include for only one item in side/context menu
- change positioning of media flags (aligned with item count)

Coordinates_MyVideoNav.xml:
- move year and genre label slightly up to match media flags and item count positioning

Coordinates_Viewtype52.xml:
- move whole view down to match title/scrollbar positioning of other horizontal views
- fix width of title and year/genre label control

Coordinates_Viewtype53.xml:
- fix width of title and year/genre label control

Coordinates_Viewtype55.xml:
- fix width of title and year/genre label control

Coordinates_Viewtype521.xml:
- fix width of title and year/genre label control

Coordinates_Viewtype532.xml:
- fix width of title and year/genre label control

Coordinates_Viewtype534.xml:
- fix width of title and year/genre label control

DialogAddonInfo.xml:
- add install date to details list
- add new info line (last used, last updated)

DialogFavourites.xml:
- change conditional onleft of scrollbar (submenu is only present during playback with active side-menu controls)
- change conditional visibility of submenu indicator (submenu is only present during playback with active side-menu controls)
- remove hide scrollbar toggle

DialogMusicInfo.xml:
- add new scrollbar for artist info dialog
- add button indicator include

DialogVideoInfo.xml:
- add fade animation to togglable dialog elements (plot, cast, extended info)
- show all buttons all the time
- improve extended info button to keep focus
- add TV show status, country, studio and release/first aired date to details list
- remove redundant information (audio and plot)
- split details and plot between two dialog pages

EventLog.xml:
- add new "Sort order" localize to sort order toggle

Font.xml:
- adjust size and width of Arial font to match appearance of default font

Includes.xml:
- add black background layer behind background video playback to WindowBackgroundImage include
- add 13th spacer to SideMenuControlsSpacer include for only one item in side/context menu
- fix alignment of item count and media flags
- add new hide media flags functionality
- change seperator of duration/size label
- rework media flags and item count to add scrolling
- add new color layer to window and dialog background
- add new Artist Slideshow image control
- change conditional visibilities to hide other background images when Artist Slideshow is active

MyGames.xml:
- add new "View: " localize to view toggle
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle
- hide view submenu button with containers that only support one viewtype

MyMusicNav.xml:
- add new "View: " localize to view toggle
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle
- hide view submenu button with containers that only support one viewtype

MyPics.xml:
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle
- remove view submenu button

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
- hide view submenu button with containers that only support one viewtype

script-skinshortcuts-static.xml:
- add conditional visibility to MyOSMC home menu entry
- point default movies and TV show widgets to new skin playlists
- change content lines to point to new skin playlists

script-skinshortcuts.xml:
- add new widget sort by, widget sort direction and widget limit options

SkinSettings.xml:
- add hide scrollbars setting formerly found in other windows
- add new hide media flags setting
- add new show original movie title in video info dialog setting
- add color setting to background section

Variables.xml:
- add new WidgetSortByLabel, WidgetSortDirectionLabel and WidgetLimitLabel variables for new widget sort by, widget sort direction and widget limit options
- improve duration variable
- replace text by localizes for Transifex translation
- add new Colorpicker-Name, SolidBackgroundColor and SolidBackgroundColor-Name variables
- remove deprecated Plot, PlotInfoDialog, PlotDialogGuide, SongLabel, SystemInfoButton94, menuStyle and hubWidgetDetails variables
- remove deprecated OtherBackgroundImage variable

Viewtype50.xml:
- add animation for view change

Viewtype51.xml:
- add animation for view change

Viewtype52.xml:
- add animation for view change

Viewtype53.xml:
- add animation for view change

Viewtype54.xml:
- add animation for view change

Viewtype55.xml:
- add animation for view change

Viewtype511.xml:
- add animation for view change

Viewtype521.xml:
- add animation for view change

Viewtype531.xml:
- add animation for view change

Viewtype532.xml:
- add animation for view change

Viewtype533.xml:
- add animation for view change

Viewtype534.xml:
- add animation for view change

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
- remove redundant music player fanart image from widgetBackground (fanart) variable

addon.xml:
- bump version to 18.2.0
