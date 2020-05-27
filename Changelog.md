**Changes**

_New_
- add standard Kodi 'Menu' key functionality to access side menu in all windows
- add new Wide low info view
- add support for Up Next addon
- add playlist button to video OSD
- add 3D depth information to GUI elements
- add new widget layouts (square and square small)
- add new 2.33:1 scope masking option

_Improved_
- make Wide low view accessible for music views
- make disabled text colour more readable
- improve widget details and window headings
- improve debug overlay
- improve overall handling of music videos
- improve playlist window
- add missing scrollbars
- rework most dialogs for consistency
- improve widget positioning and widget icon size
- improve skinshortcuts management dialog
- improve video info dialog button behaviour

_Fixed_
- fix settings button labels for 21:9 and 4:3 modes
- fix music playlist editor window
- fix side menu return button behaviour
- fix edge alignment of dialogs and windows

**Changelog v18.3.0**

_add new Wide low info view and coordinates files_
_add new Up Next addon and coordinates files_
_remove deprecated Next Up addon files_
_add new custom reset skin settings confirmation dialog and coordinates files_
_rename music home menu skinshortcuts files_
_rename video home menu skinshortcuts file_

strings.po:
- add new localize for new Wide low info view (31392)
- change localize for Next Up successor addon Up Next (31085)
- add new explanation localize for new supported Up Next addon (31393)
- add new localize for new custom reset skin settings confirmation dialog (31394)
- rework music playlist editor and player process info dialog localizes (31008, 31011, 31156)
- update skinshortcuts widget layout explanation text for new widget layouts (31370)
- add new localizes for new widget layouts (31395, 31396)
- add new localizes for new home menu and submenu item second labels as well as widget second labels in skinshortcuts management dialog (31397, 31398)
- add new localize for reset home menu items setting (31399)

14204-1.DATA.xml:
- fix label
- add shortcut second label
- fix shortcut icon

14204.DATA.xml:
- remove deprecated shortcuts
- add shortcut second labels
- fix shortcut icons

15016-1.DATA.xml:
- fix label
- add shortcut second label
- fix shortcut icon

19021-1.DATA.xml:
- fix label
- add shortcut second label
- fix shortcut icon
- remove deprecated shortcut

19021.DATA.xml:
- add shortcut second labels
- fix shortcut icons

2-1.DATA.xml:
- fix label
- add shortcut second label
- fix shortcut icon

2.DATA.xml:
- rework shortcuts
- add shortcut second labels

3.DATA.xml:
- rework shortcuts
- add shortcut second labels

31091-1.DATA.xml:
- fix label
- add shortcut second label
- fix shortcut icon

341.DATA.xml:
- add shortcut second labels

mainmenu.DATA.xml:
- add shortcut second labels
- fix shortcut icons

movies-1.DATA.xml:
- fix label
- add shortcut second label
- fix shortcut icon

movies.DATA.xml:
- fix years localize
- add shortcut second labels
- fix shurtcut icons

overrides.xml:
- change widget layout labels to localizes
- add new default layouts to default widgets
- add new widget layout properties
- adjust default widgets with new widget label IDs

programs-1.DATA.xml:
- fix label
- add shortcut second label
- fix shortcut icon

settings.DATA.xml:
- rework shortcuts
- add shortcut second labels
- fix shortcut icons

template.xml:
- rework widgetDetails variable
- adjust widget layout and widget layout slide includes of weather widget template
- rework widget layout and widget layout slide includes for new widget layouts
- rework lumos layout property group for new widget layouts
- simplify widgetBackground variable

tvshows-1.DATA.xml:
- fix label
- add shortcut second label
- fix shortcut icon

tvshows.DATA.xml:
- fix years localize
- add shortcut second labels
- fix shortcut icons

weather-1.DATA.xml:
- fix label
- add shortcut second label
- fix shortcut icon

AddonBrowser.xml:
- add SidemenuMenucontrol include
- add depth includes to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to options side menu

Coordinates_Custom_Backup.xml:
- adjust controls width to fit 150 pixel dialog edge alignment

Coordinates_Custom_Confirm_Reset_Skin_Settings.xml:
- adjust controls width to fit 150 pixel dialog edge alignment

Coordinates_Custom_Customization.xml:
- adjust controls width to fit 150 pixel dialog edge alignment

Coordinates_Custom_DialogMasking.xml:
- adjust masking dialog size for additional masking aspect ratio button

Coordinates_Custom_Disabled_Add-on.xml:
- adjust controls width to fit 150 pixel dialog edge alignment

Coordinates_Custom_Skin_SHortcuts_Help.xml:
- adjust control dimensions to match help overlay to reworked skinshortcuts dialog

Coordinates_Custom_Welcome.xml:
- adjust controls width to fit 150 pixel dialog edge alignment

Coordinates_DialogAddonSettings.xml:
- adjust controls width to fit 150 pixel dialog edge alignment

Coordinates_DialogButtonMenu.xml:
- increase width of dialog background to avoid 3D depth gap

Coordinates_DialogConfirm.xml:
- adjust controls width to fit 150 pixel dialog edge alignment

Coordinates_DialogContextMenu.xml:
- increase width of dialog background to avoid 3D depth gap

Coordinates_DialogExtendedProgressBar.xml:
- increase width of dialog background to avoid 3D depth gap

Coordinates_DialogFavourites.xml:
- adjust controls width to fit 120 pixel window edge alignment

Coordinates_DialogGameControllers.xml:
- adjust controls width to fit 150 pixel dialog edge alignment
- add new scrollbar coordinates

Coordinates_DialogKeyboard.xml:
- adjust controls width to fit 150 pixel dialog edge alignment

Coordinates_DialogNotification.xml:
- increase width of dialog background to avoid 3D depth gap

Coordinates_DialogMediaSource.xml:
- adjust controls width to fit 150 pixel dialog edge alignment

Coordinates_DialogPictureInfo.xml:
- adjust controls width to fit 150 pixel dialog edge alignment

Coordinates_DialogPVRChannelManager.xml:
- adjust controls width to fit 150 pixel dialog edge alignment
- add new scrollbar coordinates

Coordinates_DialogPVRGroupManager.xml:
- adjust controls width to fit 150 pixel dialog edge alignment
- add new scrollbar coordinates

Coordinates_DialogSelect.xml:
- increase width and hight of games settings panel to avoid 3D depth gap
- adjust controls width to fit 150 pixel dialog edge alignment
- add new scrollbar coordinates

Coordinates_DialogSettings.xml:
- adjust controls width to fit 150 pixel dialog edge alignment

Coordinates_DialogSubtitles.xml:
- add new coordinates for right list scrollbar
- adjust controls width to fit 150 pixel dialog edge alignment
- rework right list includes

Coordinates_DialogTextViewer.xml:
- fix scrollbar coordinates

Coordinates_DialogVolumeBar.xml:
- increase width of dialog background to avoid 3D depth gap

Coordinates_FileManager.xml:
- adjust controls width to fit 150 pixel dialog edge alignment
- add new scrollbar coordinates

Coordinates_Includes.xml:
- reorder dialog button coordinates
- increase width of options side menu background to avoid 3D depth gap
- increase width and hight of masking bars to avoid 3D depth gap
- increase width of scrolling label background to avoid 3D depth gap
- rework widget alignment and animations
- fix widget wide animation for scope skin version
- adjust widget tall and wide positioning and size
- adjust widget heading positioning
- add new widgetLayoutSlide-weather-OSMC include
- rework widgetLayoutSlide-tall-OSMC and widgetLayoutSlide-wide-OSMC includes for new widget sizes and positioning
- add new widgetLayoutSlide-square-OSMC and widgetLayoutSlide-square-small-OSMC includes for new widget layouts
- add new widgetLayout-weather-OSMC include
- rework widgetLayout-tall-OSMC and widgetLayout-wide-OSMC includes for new widget sizes and positioning
- add new widgetLayout-square-OSMC and widgetLayout-square-small-OSMC includes for new widget layouts
- adjust widget heading coordinates for new widget sizes and positioning
- adjust widget details coordinates for new widget sizes and positioning
- adjust widget reloading indicator coordinates for new widget sizes and positioning

Coordinates_MyMusicNav.xml:
- fix Wide view scrollbar coordinates

Coordinates_MyMusicPlaylistEditor.xml:
- rework coordinates for music playlist editor window rework
- adjust controls width to fit 120 pixel window edge alignment

Coordinates_MyVideoNav.xml:
- add coordinates for new Wide low info scrollbar

Coordinates_MyPVRGuide.xml:
- fix scrollbar coordinates

Coordinates_script-skin_helper_service-ColorPicker.xml:
- adjust controls width to fit 150 pixel dialog edge alignment

Coordinates_script-skinshortcuts.xml:
- adjust controls width to fit 150 pixel dialog edge alignment

Coordinates_SettingsCategory.xml:
- add new coordinates for buttons not adjusted for different aspect ratio modes
- adjust controls width to fit 120 pixel window edge alignment

Coordinates_SettingsProfile.xml:
- adjust controls width to fit 120 pixel window edge alignment

Coordinates_SettingsSystemInfo.xml:
- adjust controls width to fit 120 pixel window edge alignment

Coordinates_SkinSettings.xml:
- adjust controls width to fit 120 pixel window edge alignment

Coordinates_SmartPlaylistEditor.xml:
- adjust controls width to fit 150 pixel dialog edge alignment

Coordinates_SmartPlaylistRule.xml:
- adjust controls width to fit 150 pixel dialog edge alignment

Coordinates_Viewtype52.xml:
- adjust focussed cover art dimensions for better alignment

Custom_DialogMasking.xml
- add new masking aspect ratio button

Custom_Disabled_Add-on.xml:
- fix dialog animation

Custom_Overlay_Debug.xml:
- remove deprecated and add missing window fadelabels

Defaults.xml:
- add depth includes

DialogAddonInfo.xml:
- add depth include

DialogAddonSettings.xml:
- add depth include

DialogBusy.xml:
- add depth include

DialogButtonMenu.xml:
- add depth include

DialogConfirm.xml:
- add depth include

DialogContextMenu.xml:
- add depth include

DialogExtendedProgressBar.xml:
- add depth include

DialogFavourites.xml:
- add SidemenuMenucontrol include
- add depth includes to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to options side menu

DialogGameControllers.xml:
- add depth include
- add new scrollbars

DialogKeyboard.xml:
- add depth include
- fix button alignment

DialogMediaSource.xml:
- add depth include

DialogMusicInfo.xml:
- add depth include

DialogNotification.xml:
- add depth include

DialogNumeric.xml:
- add depth include

DialogPictureInfo.xml:
- add depth include

DialogPlayerProcessInfo.xml:
- rework information label formatting
- add depth include

DialogPVRChannelGuide.xml:
- add depth include

DialogPVRChannelManager.xml:
- add depth include
- add new scrollbar

DialogPVRChannelsOSD.xml:
- add depth include

DialogPVRGroupManager.xml:
- add depth include
- add new scrollbars

DialogPVRGuideSearch.xml:
- add depth include

DialogPVRInfo.xml:
- add depth include

DialogSeekBar.xml:
- add depth include

DialogSelect.xml:
- add depth includes
- adjust game settings animations
- add new scrollbar

DialogSlider.xml:
- add depth include

DialogSubtitles.xml:
- add list scrollbars
- replace overlay image
- add depth include
- add the same dialog buttons style other dialogs use

DialogTextViewer.xml:
- add depth include
- fix scrollbar

DialogVideoInfo.xml:
- add new music video information controls (similar to music info dialog)
- change cast list behaviour (triggered via window property)
- add director information line above button grouplist
- rework cast and extended info button

DialogVolumeBar.xml:
- add depth include

EventLog.xml:
- add SidemenuMenucontrol include
- add depth includes to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to options side menu

FileBrowser.xml:
- add depth include

FileManager.xml:
- add new scrollbars

Home.xml: 
- add SidemenuMenucontrol include

GameOSD.xml:
- add depth includes

Includes.xml:
- add new SidemenuMenucontrol include
- add new include files
- adjust Media Flags animations for new Wide low info view
- adjust conditional visibility of Context/Side menu indicator include for new Wide low info view
- update conditional visibility to hide time while Up Next notification is visible
- add new onload and onunload
- move dialog buttons includes to different include file
- add depth includes to masking bars

Includes_DialogSettings.xml:
- update conditional visibility to hide OSD settings while Up Next notification is visible
- add depth includes

Includes_Home.xml:
- add depth include to side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to side menu

Includes_Time_NowPlaying.xml:
- rework now playing formatting
- add new information for music video playback

Includes_Widgets.xml:
- remove deprecated widget-movement include
- add new widgetLayout-weather include
- add new widgetLayout-square and widgetLayout-square-small includes for new widget layouts
- add new widgetLayoutSlide-weather include
- add new widgetLayoutSlide-square and widgetLayoutSlide-square-small includes for new widget layouts

Includes_Windows_Dialogs.xml:
- replace FullscreenDimensions include of background images by new FullscreenOverlayDimensions include
- add depth includes to background images
- add new depth includes
- move dialog button includes from other include file
- add visibility conditions to fanart background image to prevent ASS issues

MusicOSD.xml:
- add depth include

MusicVisualisation.xml:
- adjust music information label formatting to match overall representation
- add depth include

MyGames.xml:
- add SidemenuMenucontrol include
- add depth includes to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to options side menu

MyMusicNav.xml:
- add SidemenuMenucontrol include
- add Wide low view
- add depth includes to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to options side menu

MyMusicPlaylistEditor.xml:
- rework broken music playlist editor window

MyPics.xml:
- add SidemenuMenucontrol include
- add depth includes to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to options side menu

MyPlaylist.xml:
- add SidemenuMenucontrol include
- add depth includes to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to options side menu

MyPrograms.xml:
- add SidemenuMenucontrol include
- add depth includes to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to options side menu

MyPVRChannels.xml:
- add SidemenuMenucontrol include
- fix onleft of scrollbar while kiosk mode is active
- add hidden label (ID 30) for improved window title
- add depth includes to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to options side menu

MyPVRGuide.xml:
- add SidemenuMenucontrol include
- fix visibility of submenu indicator while kiosk mode is active
- add hidden label (ID 30) for improved window title
- add depth includes to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to options side menu

MyPVRRecordings.xml:
- add SidemenuMenucontrol include
- add depth includes to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to options side menu

MyPVRSearch.xml:
- add SidemenuMenucontrol include
- fix onleft and onright of scrollbar while kiosk mode is active
- add depth includes to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to options side menu

MyPVRTimers.xml:
- add SidemenuMenucontrol include
- fix onleft and onright of scrollbar while kiosk mode is active
- add depth includes to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to options side menu

MyVideoNav.xml:
- add SidemenuMenucontrol include
- add Wide low info view
- add new scrollbar for Wide low info view
- add depth includes to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to options side menu

MyWeather.xml: 
- add SidemenuMenucontrol include
- add conditional visibility to hide window content, visible animation and busy dialog imitation while weather data is being loaded
- add depth includes to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to options side menu

PlayerControls.xml:
- add depth include

Pointer.xml:
- add depth include

script-skin_helper_service-Color-Picker.xml:
- add new onload and onunload for improved debug dialog
- add depth include
- add missing time include
- remove palette button

script-skin_helper_service-Color-Picker.xml:
- add new onload and onunload for improved debug dialog
- change heading control to reflect currently selected colour name

script-skinshortcuts.xml:
- add new onload and onunload for improved debug dialog
- replace FullscreenDimensions include of background images by new FullscreenOverlayDimensions include
- add depth includes
- add new scrollbar

script-skinshortcuts-static.xml:
- rework default home screen layout for new widget sizes and positioning as well as new widget layouts
- rework default submenus
- simplify widgetBackground variable

script-upnext-stillwatching-simple.xml:
- add new onload and onunload for improved debug dialog
- add depth include

script-upnext-stillwatching.xml:
- add new onload and onunload for improved debug dialog
- add depth include

script-upnext-upnext-simple.xml:
- add new onload and onunload for improved debug dialog
- add depth include

script-upnext-upnext.xml:
- add new onload and onunload for improved debug dialog
- add depth include

SettingsCategory.xml: 
- add menucontrol
- adjust buttons not adapting to different aspect ratio modes
- add depth includes to settings quick-nav menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to quick-nav menu

SettingsProfile.xml:
- add depth includes to settings quick-nav menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to quick-nav menu

SettingsSystemInfo.xml:
- add depth includes to settings quick-nav menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode
- add onback to quick-nav menu

SkinSettings.xml:
- rework Next Up supported addon button for new Up Next addon
- change window heading to use global heading variable
- change skin setting reset button to first open confirmation dialog
- add dividers and adjust heading formatting and alignment to match settings appearance
- fix reset home menu items setting label
- add new onclick condition to masking toggle button for new masking aspect ratio

SmartPlaylistEditor.xml:
- add depth include

SmartPlaylistRule.xml:
- add depth include

Variables.xml:
- adjust colour values of DisabledColor variable
- adjust VideoPlayerTitle variable to show year of movies and TV shows in video player info dialog title
- add new UpNextTitle variable
- rework addon-upnext variable for new Up Next addon
- add new explanation text for Up Next addon to SkinSettingsExplanation variable
- rework HeadingLabelPrimary variable
- add new ContentTypeMyPlaylist variable for reworked playlist window
- adjust VideoPlayerTitle, MusicNextPlaying1, MusicNextPlaying2 and VideoInfoLabel variables to match overall representation of movie/TV show/album title and year
- adjust SubtitleLanguage variable to reflect whether subtitles are disabled
- add new SubtitleDownload for improved subtitle dialog

Variables_Skinshortcuts.xml:
- add new values to skinshortcuts-size variable for new widget layouts

VideoFullScreen.xml:
- update conditional visibility to hide OSD elements while Up Next notification is visible
- adjust music video info dialog information to match representation in other music video windows/dialogs
- add depth include
- add new animation to masking bars for new masking aspect ratio

VideoOSD.xml:
- update conditional visibility to hide OSD elements while Up Next notification is visible
- add new playlist button (like with MusicOSD)
- add depth includes
- add new masking aspect ratio texture to masking dialog button

VideoOSDBookmarks.xml:
- add depth includes

Viewtype50.xml:
- add new image for songs and videos while playlist window is visible
- add conditional visibility to show list in playlist window

Viewtype521.xml:
- enable view in music library sections

Viewtype522.xml:
- adjust visibility condition to prevent view from being used in TV show seasons overview

Viewtype54.xml:
- add visibility condition to hide user rating label, if disabled in skin settings
- adjust album info fadelabel to match overall representation of album title and year

Textures.xbt:
- update textures file with new button highlight textures
- update textures file with new scope aspect ratio video OSD texture

addon.xml:
- bump version to 18.3.0
