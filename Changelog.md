**Changes**

_New_
- add new pre-defined widgets
- add setting to change whether video info dialog shows details or plot first
- add setting to set a solid colour instead of background images
- add audio and subtitle language information to media flags
- add setting to toggle media flags information shown (first)
- add new seek indicator to audio and video player
- add new scope version
- add new scrolling label
- add new never hide music information during playback setting
- add skin settings explanations
- add setting to hide item count

_Improved_
- rework home menu customization dialogs
- improve sort by and sort order toggles
- improve video info dialog (animations and buttons)
- improve alignment and positioning of item count and media flags
- show view toggle only when more than one view is available
- improve info dialogs (more information/layout with video and addon info dialogs)
- update Artist Slideshow integration (v3 update)
- improve OSD animations
- show item count with empty containers
- improve music player during radio playback
- improve visible window elements when busy dialog is active
- let live TV and radio OSD listen to Kodi OSD settings

_Fixed_
- move hide scrollbars setting to skin settings window
- hide MyOSMC home menu entry and widget on non-OSMC systems
- fix overlapping in views with big horizontal titles
- add scrollbar to music album info dialog (if details list is too long)
- fix now playing dialog for radio and live TV playback
- fix kiosk mode behaviour

**Changelog v18.2.0**

_add new skin playlists and update existing ones_
_add new coordinates file for seek bar dialog_
_add new masking OSD dialog and coordinates file_
_add new custom Skin Shortcuts Help dialog and coordinates file_

strings.po:
- change localize for new hide scrollbars option (31005)
- add new localizes for new widget sort by, widget sort direction and widget limit options (31175, 31176, 31177)
- add new localizes for new pre-defined widgets and reworked home menu customization dialogs (31178-31232)
- add new localizes for improved sort by and sort order toggles (31233, 31234)
- add new localizes for additional widgets per script (31235, 31236)
- add new localize hide media flags setting (31237)
- add new localizes for Transifex translation (31238-31266)
- change localize for new movie info dialog setting (31170)
- change localize Artist Slideshow background setting (31034)
- change localize for updated media flags setting (31237)
- add new localize for masking setting (31267)
- change "hide" to "disable" (31005, 31105, 31147, 31148, 31149)
- add new localize for scrolling label setting (31268)
- update language file header
- replace deprecated localize with new never hide music information during playback setting localize (31040)
- update localize for always show settings link warning (31051)
- move disable scrolling label setting localize (31053)
- change "color" to "colour" in all localizes (31062, 31162, 31163, 31164, 31165, 31166, 31266)
- move masking toggle localize (31065)
- replace deprecated localizes with new skin setting explanation localizes (31098, 31140)
- remove " (default: ...)" from all settings heading localizes (31100, 31101, 31102, 31104, 31108, 31109, 31110, 31111, 31129, 31132, 31143, 31170, 31237)
- update localize for open music fullscreen automatically setting (31142)
- add new skin settings explanation localizes (31267-31389)
- add new localizes for item count hide setting (31390, 31391)

AddonBrowser.xml:
- remove deprecated view toggle
- remove hide scrollbar toggle
- fix side-menu coordinates
- add new "Sort order" localize to sort order toggle
- rework look controls
- add masking bars include
- add visibility conditions to hide submenu when kiosk mode is active

Coordinates_AddonBrowser.xml:
- add fourth condition to each coordinate include for new masking mode

Coordinates_Custom_Backup.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_Custom_Cache_Progress.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_Custom_Customization.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_Custom_Disabled_Add-on.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_Custom_Overlay_Debug.xml: 
- add fourth condition to each coordinate include for new masking mode
- add new debug grid coordinates include

Coordinates_Custom_Welcome.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogAddonInfo.xml:
- adjust hight of details list
- adjust position and hight of description textbox
- add coordinates for new info line (last used, last updated)
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogAddonSettings.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogBusy.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogButtonMenu.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogConfirm.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogContextMenu.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogExtendedProgressBar.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogFavourites.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogFullScreenInfo.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogGameControllers.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogKeyboard.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogMediaSource.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogMusicInfo.xml:
- adjust hight of details list
- adjust position and hight of plot textbox
- add coordinates for scrollbar
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogNotification.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogNumeric.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogPictureInfo.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogPlayerProcessInfo.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogPVRChannelGuide.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogPVRChannelManager.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogPVRChannelsOSD.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogPVRGroupManager.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogPVRGuideSearch.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogPVRInfo.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogSeekBar.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogSelect.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogSettings.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogSlider.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogSubtitles.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogTextViewer.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogVideoInfo.xml:
- adjust hight of details list
- adjust position and hight of plot textbox
- add fourth condition to each coordinate include for new masking mode

Coordinates_DialogVolumeBar.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_EventLog.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_FileBrowser.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_FileManager.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_GameOSD.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_Home.xml: 
- add fourth condition to each coordinate include for new masking mode
- move options side menu animations back to Home.xml file

Coordinates_Includes.xml:
- add SideMenuControlsSpacer_coords13 include for only one item in side/context menu
- change positioning of media flags (aligned with item count)
- add fourth condition to each coordinate include for new masking mode
- add new firstletter_coords include for new first letter scrolling label

Coordinates_LoginScreen.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_MusicOSD.xml: 
- add fourth condition to each coordinate include for new masking mode
- fix coordinates for new radio specific controls
- remove deprecated coordinates

Coordinates_MusicVisualisation.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_MyGames.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_MyMusicNav.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_MyMusicPlaylistEditor.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_MyPics.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_MyPlaylist.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_MyPrograms.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_MyPVRChannels.xml: 
- add fourth condition to each coordinate include for new masking mode
- fix visbility conditions to hide most unnecessary information when list is empty

Coordinates_MyPVRGuide.xml: 
- add fourth condition to each coordinate include for new masking mode
- add new LiveTV and Radio fallback icons to channel image

Coordinates_MyPVRRecordings.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_MyPVRSearch.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_MyPVRTimers.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_MyVideoNav.xml:
- move year and genre label slightly up to match media flags and item count positioning
- add fourth condition to each coordinate include for new masking mode

Coordinates_MyWeather.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_PlayerControls.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_script-skinshortcuts.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_script-skin_helper_service-ColorPicker.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_Settings.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_SettingsCategory.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_SettingsProfile.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_SettingsSystemInfo.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_SkinSettings.xml: 
- add fourth condition to each coordinate include for new masking mode
- fix coordinates of skin settings explanation text box

Coordinates_SmartPlaylistEditor.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_SmartPlaylistRule.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_VideoFullScreen.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_VideoOSD.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_VideoOSDBookmarks.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_Viewtype50.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_Viewtype51.xml: 
- add fourth condition to each coordinate include for new masking mode
- remove deprecated Viewtype51_coords13 include

Coordinates_Viewtype511.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_Viewtype52.xml:
- move whole view down to match title/scrollbar positioning of other horizontal views
- fix width of title and year/genre label control
- add fourth condition to each coordinate include for new masking mode

Coordinates_Viewtype521.xml:
- fix width of title and year/genre label control
- add fourth condition to each coordinate include for new masking mode

Coordinates_Viewtype53.xml:
- fix width of title and year/genre label control
- add fourth condition to each coordinate include for new masking mode

Coordinates_Viewtype531.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_Viewtype532.xml:
- fix width of title and year/genre label control
- add fourth condition to each coordinate include for new masking mode

Coordinates_Viewtype533.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_Viewtype534.xml:
- fix width of title and year/genre label control
- add fourth condition to each coordinate include for new masking mode

Coordinates_Viewtype54.xml: 
- add fourth condition to each coordinate include for new masking mode

Coordinates_Viewtype55.xml:
- fix width of title and year/genre label control
- add fourth condition to each coordinate include for new masking mode

Custom_Backup.xml: 
- add masking bars include

Custom_Customization.xml: 
- add masking bars include

Custom_Disabled_Add-on.xml: 
- add masking bars include

Custom_Overlay_Debug.xml: 
- add coordinates include

Custom_Welcome.xml: 
- add masking bars include

DialogAddonInfo.xml:
- add install date to details list
- add new info line (last used, last updated)
- fix buttons coordinates
- add masking bars include

DialogAddonSettings.xml: 
- fix visibility of button indicators to hide when shutdown menu is active
- add masking bars include

DialogButtonMenu.xml: 
- add masking bars include

DialogConfirm.xml: 
- add masking bars include

DialogContextMenu.xml: 
- add masking bars include

DialogFavourites.xml:
- change conditional onleft of scrollbar (submenu is only present during playback with active side-menu controls)
- change conditional visibility of submenu indicator (submenu is only present during playback with active side-menu controls)
- remove hide scrollbar toggle
- change item count to match overall behaviour
- add masking bars include
- add animation to hide item count when busy dialog is visible and container is empty
- add visibility conditions to hide submenu when kiosk mode is active

DialogGameControllers.xml: 
- fix visibility of button indicators to hide when shutdown menu is active
- add masking bars include

DialogKeyboard.xml: 
- add masking bars include

DialogMediaSource.xml: 
- add masking bars include

DialogMusicInfo.xml:
- add new scrollbar for artist info dialog
- add button indicator include
- fix visibility of button indicators to hide when shutdown menu is active
- add masking bars include
- add visibility conditions to hide buttons when kiosk mode is active
- add close button that's visible when kiosk mode is active and no other buttons are visible

DialogNumeric.xml: 
- add masking bars include

DialogPictureInfo.xml: 
- fix visibility of button indicators to hide when shutdown menu is active
- add masking bars include

DialogPlayerProcessInfo.xml:
- add visibility condition to hide dialog while shutdown menu is open
- replace OSD animation by new animation includes
- add new LiveTV and Radio fallback icons to player icon
- fix conditional visibility of PVR info for radio playback
- add visbility condition to hide video player debug information if no video is being played back

DialogPVRChannelGuide.xml:
- add new LiveTV and Radio fallback icons to channel icon

DialogPVRChannelManager.xml: 
- fix visibility of button indicators to hide when shutdown menu is active
- add masking bars include

DialogPVRChannelsOSD.xml:
- add new LiveTV and Radio fallback icons to channel icon

DialogPVRGroupManager.xml:
- fix visibility of button indicators to hide when shutdown menu is active
- add masking bars include

DialogPVRGuideSearch.xml: 
- add masking bars include

DialogPVRInfo.xml: 
- add masking bars include
- add new LiveTV and Radio fallback icons to channel icon

DialogSeekBar.xml:
- add slider control for new seek indicator

DialogSelect.xml:
- add visibility condition to hide dialog while shutdown menu is open
- add Visible and Hidden animation to game OSD settings
- fix visibility of button indicators to hide when shutdown menu is active
- add masking bars include

DialogSubtitles.xml:
- fix visibility of button indicators to hide when shutdown menu is active
- add masking bars include

DialogTextViewer.xml: 
- add masking bars include

DialogVideoInfo.xml:
- add fade animation to togglable dialog elements (plot, cast, extended info)
- show all buttons all the time
- improve extended info button to keep focus
- add TV show status, country, studio and release/first aired date to details list
- remove redundant information (audio and plot)
- split details and plot between two dialog pages
- change formatting of audio and subtitle labels
- fix visibility of button indicators to hide when shutdown menu is active
- add masking bars include
- add visibility conditions to hide buttons when kiosk mode is active

EventLog.xml:
- add new "Sort order" localize to sort order toggle
- add masking bars include
- add visibility conditions to hide submenu when kiosk mode is active

FileManager.xml:
- change item count to match overall behaviour
- add masking bars include
- add animation to hide item count when busy dialog is visible and container is empty

Font.xml:
- adjust size and width of Arial font to match appearance of default font

GameOSD.xml:
- add visibility condition to hide dialog while shutdown menu is open
- replace OSD animations by new animation includes

Home.xml: 
- add masking bars include

Includes.xml:
- add black background layer behind background video playback to WindowBackgroundImage include
- add 13th spacer to SideMenuControlsSpacer include for only one item in side/context menu
- fix alignment of item count and media flags
- add new hide media flags functionality
- change seperator of duration/size label
- rework media flags and item count to add scrolling
- add new colour layer to window and dialog background
- add new Artist Slideshow image control
- change conditional visibilities to hide other background images when Artist Slideshow is active
- add onload for new media flags setting
- update media flags with new audio and subtitle language information
- add new OSD animation includes
- add new include file
- add new onload for masking setting
- change item count to be visible with empty containers as well
- fix visibility of button indicators to hide when shutdown menu is active
- add new MaskingBars include
- add new first letter scolling indicator to time include
- fix audio now playing/progress and radio/live TV now playing/progress information
- add animation to hide item count when busy dialog is visible and container is empty
- add new Skin Shortcuts Help dialog include file
- change conditional visibility of overlay to react to new never hide music information during playback setting
- add visibility conditions to hide context/sidemenu indicators when kiosk mode is active
- add new onloads for hide item count setting

Include_DialogSettings.xml:
- add visibility condition to hide dialog while shutdown menu is open
- replace OSD animations by new animation includes
- fix visibility of button indicators to hide when shutdown menu is active
- add masking bars include

Include_Home_OSMC.xml:
- fix visibility of button indicators to hide when shutdown menu is active
- move options side menu animations back from Coordinates_Home.xml file

LoginScreen.xml: 
- fix visibility of button indicators to hide when shutdown menu is active
- add masking bars include

MusicOSD.xml:
- add visibility condition to hide dialog while shutdown menu is open
- replace OSD animations by new animation includes
- add new radio playback controls (change channel, record, access EPG OSD dialogs)

MusicVisualisation.xml:
- change visibility conditions to hide OSD elements when OSD dialogs are active
- replace OSD animations by new animation includes
- add masking bars include
- add new radio playback information (now playing and playing next)
- change visibility conditions of OSD elements to show up correctly during radio playback
- add missing fade animations to OSD elements
- add radio playback specific playback position and progress information
- change conditional visibilities to react to new never hide music information during playback setting

MyGames.xml:
- add new "View: " localize to view toggle
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle
- rework look controls
- add masking bars include
- add visibility conditions to hide submenu when kiosk mode is active

MyMusicNav.xml:
- add new "View: " localize to view toggle
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle
- rework look controls
- add masking bars include
- add visibility conditions to hide submenu when kiosk mode is active

MyPics.xml:
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle
- rework look controls
- add masking bars include
- add visibility conditions to hide submenu when kiosk mode is active

MyPlaylist.xml:
- fix side-menu coordinates
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle
- add masking bars include
- add visibility conditions to hide submenu when kiosk mode is active

MyPrograms.xml:
- add new "View: " localize to view toggle
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle
- rework look controls
- add masking bars include
- add visibility conditions to hide submenu when kiosk mode is active

MyPVRChannels.xml:
- fix side-menu coordinates
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle
- change item count to match overall behaviour
- add masking bars include
- add new LiveTV and Radio fallback icons to channel icon
- fix visbility conditions to hide most unnecessary information when list is empty
- add animation to hide item count when busy dialog is visible and container is empty
- add visibility conditions to hide submenu when kiosk mode is active

MyPVRGuide.xml:
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle
- add masking bars include
- add new LiveTV and Radio fallback icons to channel icon
- add visibility conditions to hide submenu when kiosk mode is active

MyPVRRecordings.xml:
- fix side-menu coordinates
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle
- change item count to match overall behaviour
- add masking bars include
- add new LiveTV and Radio fallback icons to channel icon
- add animation to hide item count when busy dialog is visible and container is empty
- add visibility conditions to hide submenu when kiosk mode is active

MyPVRSearch.xml:
- fix side-menu coordinates
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle
- change item count to match overall behaviour
- add masking bars include
- add animation to hide item count when busy dialog is visible and container is empty
- add visibility conditions to hide submenu when kiosk mode is active

MyPVRTimers.xml:
- fix side-menu coordinates
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle
- change item count to match overall behaviour
- add masking bars include
- add animation to hide item count when busy dialog is visible and container is empty
- add visibility conditions to hide submenu when kiosk mode is active

MyVideoNav.xml:
- add new "View: " localize to view toggle
- remove hide scrollbar toggle
- add new "Sort order" localize to sort order toggle
- rework look controls
- add masking bars include
- add visibility conditions to hide submenu when kiosk mode is active

MyWeather.xml: 
- change weather provider info control to match item count layout
- add masking bars include
- add visibility conditions to hide submenu when kiosk mode is active

PlayerControls.xml:
- update player controls to match music and video OSD controls

script-skinshortcuts-static.xml:
- add conditional visibility to MyOSMC home menu entry
- point default movies and TV show widgets to new skin playlists
- change content lines to point to new skin playlists

script-skinshortcuts.xml:
- add new widget sort by, widget sort direction and widget limit options
- fix visibility of button indicators to hide when shutdown menu is active
- add masking bars include
- replace dialogButtonBackground include by dialogButton image controls to work together properly with new Skin Shortcuts Help dialog
- add new help button

script-skin_helper_service-ColorPicker.xml: 
- fix visibility of button indicators to hide when shutdown menu is active
- add masking bars include

Settings.xml: 
- add masking bars include

SettingsCategory.xml: 
- add masking bars include

SettingsProfile.xml: 
- fix visibility of button indicators to hide when shutdown menu is active
- add masking bars include

SettingsScreenCalibration.xml: 
- add masking bars include

SettingsSystemInfo.xml: 
- fix visibility of button indicators to hide when shutdown menu is active
- add masking bars include

SkinSettings.xml:
- add hide scrollbars setting formerly found in other windows
- add new show original movie title in video info dialog setting
- add colour setting to background section
- add setting to toggle media flags information shown (first)
- add new masking setting
- add masking bars include
- remove deprecated OSD info PVR channel switch toggle (OSD now listens to Kodi toggle)
- add new disable scrolling label setting
- update localizes
- add new never hide music information during playback setting
- remove deprecated warning label for multi-image fanart
- remove Skin Helper Backgrounds addon from supported addons section
- remove deprecated lock PVR guide view setting
- replace hide settings warning text box by new settings explanation text box
- add new hide item count setting

SmartPlaylistEditor.xml: 
- change text colour of heading labels
- add masking bars include

SmartPlaylistRule.xml: 
- change text colour of heading label
- add masking bars include

Variables.xml:
- add new WidgetSortByLabel, WidgetSortDirectionLabel and WidgetLimitLabel variables for new widget sort by, widget sort direction and widget limit options
- improve duration variable
- replace text by localizes for Transifex translation
- add new Colorpicker-Name, SolidBackgroundColor and SolidBackgroundColor-Name variables
- remove deprecated Plot, PlotInfoDialog, PlotDialogGuide, SongLabel, SystemInfoButton94, menuStyle and hubWidgetDetails variables
- remove deprecated OtherBackgroundImage variable
- add AudioSimple, AudioChannelsSimple and SubtitleSimple variables for new langauge media flags information
- change ContentType and ContentTypeFavourites variable to show plural with empty containers
- add new ContentTypeFileManager20 and ContentTypeFileManager21 variables
- update VideoPlayerTitle variable to only show live TV information when EPG information is available
- update PlayerIcon variable to use Player.Icon for use in video and music player
- new new conditions to MusicNextPlaying variables for music visualisation radio next playing information
- add new SkinSettingsExplanation and SkinShortcutsExplanation variables

VideoFullScreen.xml:
- fix animation conditions (don't wait for VideoOSD anmiation + move while player process info dialog is open)
- update visibility conditions to hide OSD elements when OSD dialogs are active
- replace OSD animations by new animation includes
- fix visibility to hide OSD while new masking dialog is active
- add masking bars
- replace visible and hidden animations by VisibleFadeAnimation include
- change visibility conditions of OSD elements to show up correctly during live TV playback
- add missing fade animations to OSD elements
- remove deprecated videoinfolivetvswitch setting from conditional visibilities
- add new LiveTV fallback icon to player icon during live TV playback

VideoOSD.xml:
- add visibility condition to hide dialog while player process info dialog or shutdown menu are open
- replace OSD animations by new animation includes
- fix visibility to hide OSD while new masking dialog is active
- change onleft of controls (new masking dialog button)
- add new Masking button
- add back channel up and down buttons during live TV playback

Viewtype50.xml:
- add fadetime to image
- add missing visible param condition to image
- add new visibility condition to show image when container is not empty or when container is empty and folder up icon is shown

Viewtype51.xml:
- change coordinates include of image-51-video include
- add new visibility condition to show image when container is not empty or when container is empty and folder up icon is shown

Viewtype511.xml:
- add new image-51-video include (like with Viewtype51)
- add new visibility condition to show image when container is not empty or when container is empty and folder up icon is shown

Viewtype52.xml:
- add new visibility condition to show image when container is not empty or when container is empty and folder up icon is shown

Viewtype521.xml:
- add new visibility condition to show image when container is not empty or when container is empty and folder up icon is shown

Viewtype53.xml:
- add new visibility condition to show image when container is not empty or when container is empty and folder up icon is shown

Viewtype531.xml:
- add new visibility condition to show image when container is not empty or when container is empty and folder up icon is shown

Viewtype532.xml:
- add new visibility condition to show image when container is not empty or when container is empty and folder up icon is shown

Viewtype533.xml:
- add new visibility condition to show image when container is not empty or when container is empty and folder up icon is shown

Viewtype534.xml:
- add new visibility condition to show image when container is not empty or when container is empty and folder up icon is shown

Viewtype54.xml:
- add new visibility condition to show image when container is not empty or when container is empty and folder up icon is shown

Viewtype55.xml:
- add new visibility condition to show image when container is not empty or when container is empty and folder up icon is shown

Textures.xbt:
- update textures file with new, bigger OSMC logo file
- update textures file with improved media flags icons
- update textures file with new seek indicator icon
- update textures file with new seek masking OSD icons

mainmenu.DATA.xml:
- add conditional visibility to MyOSMC home menu entry

overrides.xml:
- add general and widget groupings to sort user dialogs for home menu entries and widgets in home menu customization dialog
- point default movies and TV show widgets to new skin playlists
- change default music widget group to circumvent v18 skinshortcuts bug (missing/wrong localize for "music")
- remove unused "square" widget icon layout
- add new widget sort by, widget sort direction and widget limit properties
- remove broken Skin Helper Backgrounds support

template.xml:
- add new widget sort by, widget sort direction and widget limit properties
- change content line for new widget sort by, widget sort direction and widget limit properties
- remove redundant music player fanart image from widgetBackground (fanart) variable

addon.xml:
- bump version to 18.2.0
