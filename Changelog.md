**Changes**

_New_
- add new video player OSD settings (show OSD after beginning of playback and before end of playback)
- add new second video info dialog screen (with extended rating, audio and subtitle information and bigger plot text box)
- add new wall info view (based on wall view)
- add new adjust representation of video duration setting
- add new multi image (folder) background option
- add new individual background option for home menu entries
- add new options for music OSD to automatically show
- add user rating to music and video library
- add new side-menu player controls
- add new options to hide watched indicator in video library and listened to indicator in music library

_Improved_
- add audio information to video info dialog
- use font type for bold, light and italic instead of label formatting (where possible)
- prevent stacking of window/dialog text during background video playback
- show special watched indicator icons for videos watched more than once
- add listened to indicator for music

_Fixed_
- only offer rip CD feature when an audio CD is present

**Changelog v18.0.1**

Addon.Browser.xml:
- replace label formatting with light font
- replace label formatting with bold font
- move skin-related onloads to include
- clean-up window header
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include

Custom_AutoMusicVis.xml:
- add new custom dialog for new music OSD auto option

Custom_Backup.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

Custom_Customization.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

Custom_Disabled_Add-on.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

Custom_Welcome.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

DialogAddonInfo.xml:
- fix syntax
- replace label formatting with light font
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

DialogAddonSettings.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

DialogAddonSettings.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

DialogConfirm.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include
- move DialogZoomAnimation include to affect background as well

DialogFavourites.xml:
- replace label formatting with light font
- replace old bold font
- remove onright of list
- add item count
- adjust conditional visibility of submenu indicator to hide it when container is empty
- fix top positioning of look controls
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include

DialogFullScreenInfo.xml:
- remove info dialog

DialogGameControllers.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

DialogKeyboard.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

DialogMediaSource.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

DialogMusicInfo.xml:
- replace label formatting with light font
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include
- add user rating button
- add play count and last played date & time information

DialogNumeric.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

DialogPictureInfo.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

DialogPlayerProcessInfo.xml:
- replace label formatting with light font

DialogPVRChannelGuide.xml:
- replace label formatting with light font
- replace label formatting with bold font

DialogPVRChannelManager.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

DialogPVRGroupManager.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

DialogPVRGuideSearch.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

DialogPVRInfo.xml:
- replace label formatting with light font
- replace label formatting with bold font
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

DialogSeekBar.xml:
- remove PVR channel number input dialog

DialogSelect.xml:
- replace label formatting with light font
- replace label formatting with bold font
- remove WindowFadeAnimation include
- remove Window Background section
- add new DialogFanart include

DialogSubtitles.xml:
- remove deprecated WindowFadeBackgroundImage include
- remove deprecated animations
- add new dialog background

DialogTextViewer.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

DialogVideoInfo.xml:
- add onload and onunload for new second info screen
- fix conditional visibility of poster/actor images, info list and cast list for use with new second info screen
- fix positioning of actor image
- add audio information
- adjust plot text box and make it show plot outline (shorter and no spoilers)
- fix positioning of cast list
- fix positioning of cast list scrollbar
- add second info screen (with extended rating, audio and subtitle information and bigger plot text box)
- add conditional visiblity to only show play and return button in second info screen
- add extended info button
- replace label formatting with light font
- remove deprecated onload
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include
- add user rating button
- add play count and last played date & time information

EventLog.xml:
- replace label formatting with light font
- replace label formatting with bold font
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include

FileBrowser.xml:
- replace label formatting with light font
- replace label formatting with bold font
- remove WindowFadeAnimation include
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

FileManager.xml:
- replace label formatting with light font
- replace label formatting with bold font

Font.xml:
- add bold, light and italic version to each font size

Home.xml:
- move skin-related onloads to include
- clean-up window header

Includes.xml:
- add new include file for new view
- replace label formatting with light font
- change background image include for new multi image (folder) background option
- add CustomBackgroundFolderDuration include for new multi image (folder) background option
- add new Onloads include for skin-related onloads
- replace DialogTextBackground.png of WindowFadeBackgroundImage include by overlay image
- fix dialogButtonBackground include (remove border and only show two horizontal lines as borders)
- add new onload for new music OSD auto option
- simplify WindowBackgroundImage include (remove params and animations not needed)
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include
- add new SideMenuControls include for new sub-menu player controls
- add new SideMenuControlsSpacer include for new sub-menu player controls

Include_DialogSettings.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

Include_Home_OSMC.xml:
- replace label formatting with light font
- replace label formatting with bold font

Includes_Widgets.xml:
- replace label formatting with bold font

LoginScreen.xml:
- replace label formatting with light font
- replace label formatting with bold font
- move skin-related onloads to include
- clean-up window header

MusicVisualisation.xml:
- replace label formatting with light font
- replace label formatting with bold font

MyGames.xml:
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include

MyMusicNav.xml:
- fix width of options hidden side-menu button
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include
- remove clean library option from side-menu
- hide update library option from side-menu in add-on view

MyPics.xml:
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include

MyPlaylist.xml:
- fix onup and ondown of sub-menu
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include

MyPrograms.xml:
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include

MyPVRChannels.xml:
- fix alignment of plot textbox
- replace label formatting with light font
- replace label formatting with bold font
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include

MyPVRGuide.xml:
- fix alignment of plot textbox
- replace label formatting with light font
- replace label formatting with bold font
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include

MyPVRRecordings.xml:
- fix alignment of plot textbox
- replace label formatting with light font
- replace label formatting with bold font
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include

MyPVRSearch.xml:
- replace label formatting with light font
- replace label formatting with bold font
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include
 
MyPVRTimers.xml:
- replace label formatting with light font
- replace label formatting with bold font
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include

MyVideoNav.xml:
- add new view 534 and rename 531, 532 and 533
- add new scrollbar for new wall info view (old wall info is now wall small info)
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include
- remove clean library option from side-menu
- hide update library option from side-menu in add-on view

MyWeather.xml:
- remove onclick, onup, ondown and onright
- fix top positioning of look controls
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include

script-nextup-notification-NextUpInfo.xml:
- replace label formatting with light font

script-nextup-notification-StillWatchingInfo.xml:
- replace label formatting with light font

script-skin_helper_service-ColorPicker.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

script.skinshortcuts.xml:
- add edit background option to home menu customization dialog
- add edit background duration option to home menu customization dialog
- remove WindowFadeBackgroundImage include
- move DialogZoomAnimation include to affect background as well
- remove WindowFadeAnimation include
- add new dialog background

script.skinshortcuts-static-xml:
- fix conditional visibility for Rip CD feature (only show for audio CDs)
- remove background fallback of widgetBackground variable (empty value)
- add conditional visibility to watched/listened to indicator background for new option to hide these indicators

SettingsCategory.xml:
- move skin-related onloads to include
- clean-up window header
- fix top positioning of look controls
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include

SettingsProfile.xml:
- fix top positioning of look controls
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include

SettingsSystemInfo.xml:
- fix top positioning of look controls
- add animation to shift up side-menu controls when side-menu player controls are active
- add SideMenuControlsSpacer include
- add SideMenuControls include

SkinSettings.xml:
- add new adjust representation of video duration setting
- replace label formatting with italic font
- move skin-related onloads to include
- clean-up window header
- change IDs of skin settings categories
- change background settings for new multi image (folder) background option
- add skin helper backgrounds script as requirement for home menu customization
- add skin helper backgrounds script as recommended addon
- add new captions for video and music OSD sections
- add new option to show music OSD after set time during playback
- add new toggle to adjust time after which music OSD appears during playback
- add new user rating option
- add new option to hide new sub-menu player controls
- add new options to hide watched indicator in video library and listened to indicator in music library

SmartPlaylistEditor.xml:
- remove deprecated WindowFadeBackgroundImage include
- remove deprecated animation
- add new DialogFanart include

SmartPlaylistRule.xml:
- remove deprecated WindowFadeBackgroundImage include
- add new DialogFanart include

Variables.xml:
- update VideoPlayerPlot, VideoPlayerTitle and VideoPlayerNext variables for new OSD settings
- add new PlotInfoDialog variable (preferring plot outline over plot for video info dialog)
- add new AudioChannels.1-.4 variables for new second info dialog screen
- add new AudioCodec.1-.4 variables for new second info dialog screen
- adjust Duration variable for new video duration setting
- change OSMCBackgroundImage variable for new multi image (folder) background option
- add new addon-skinhelperbackgrounds variable for new recommended addon
- add user rating to VideoInfoLabel variable
- add user rating to MusicInfoLabel variable
- add user rating to Label2 variable
- add user rating to Label2-episodes variable
- add new LabelUserRating variable
- add new ContentTypeFavourites variable for favourites dialog
- update StatusOverlay and StatusOverlayWide variables with new watched indicator icons (watched more than once)

VideoFullScreen.xml:
- add onloads for OSD settings alarm
- adjust conditional visibility of progress bar and info dialog for new OSD settings
- add elements formerly present in fullscreen info and seekbar dialog
- replace label formatting with bold font
- replace label formatting with light font

Viewtype50.xml:
- replace label formatting with light font
- replace label formatting with bold font

Viewtype51.xml:
- fix alignment of plot textbox
- replace label formatting with light font
- replace label formatting with bold font

Viewtype511.xml:
- fix alignment of plot textbox
- replace label formatting with light font
- replace label formatting with bold font

Viewtype52.xml:
- add conditional visibility to watched/listened to indicator background for new option to hide these indicators

Viewtype521.xml:
- add conditional visibility to watched/listened to indicator background for new option to hide these indicators

Viewtype53.xml:
- add conditional visibility to watched/listened to indicator background for new option to hide these indicators

Viewtype531.xml:
- fix alignment of plot textbox
- adjust size and amount of movie poster thumbs for new wall info view
- add user rating
- add conditional visibility to watched/listened to indicator background for new option to hide these indicators

Viewtype532.xml:
- fix size of collection and watched/listened to indicators
- add conditional visibility to watched/listened to indicator background for new option to hide these indicators

Viewtype533.xml:
- make old wall info view new wall small info view
- add user rating
- add conditional visibility to watched/listened to indicator background for new option to hide these indicators

Viewtype534.xml:
- new viewtype file for old wall low view
- add conditional visibility to watched/listened to indicator background for new option to hide these indicators

Viewtype54.xml:
- replace label formatting with light font
- replace label formatting with bold font
- add user rating
- add back watched/listened to indicator

Viewtype55.xml:
- add back watched/listened to indicator

remove Default.png file

SourceSansPro-Italic.ttf:
- add new font style file

SourceSansPro-Light.ttf:
- add new font style file

SourceSansPro-Regular.ttf:
- add new font file

SourceSansPro-Semibold.ttf:
- add new font style file

strings.po:
- add new localizes for extended ratings in second video info dialog screen (31120, 31121, 31122)
- add new localizes for new OSD settings (31123, 31124, 31125, 31126, 31127, 31128, 31129, 31130, 31131, 31132)
- change view localizes (31112, 31113, 31114, 31116, 31117)
- add new localize for new wall info view (31133)
- add new localize for new video duration setting (31134)
- add new localizes for new multi image (folder) background option (31135, 31136, 31137, 31138)
- add new localizes for reset path of new background option (31139)
- add new localizes for new recommended addon (31140)
- add new localizes for new music OSD options (31074, 31141, 31142, 31143, 31144, 31145)
- add new localize for new user rating option (31146)
- add new localize for new sub-menu player controls hide option (31147)
- add new localizes for new hide watched indicator in video library and hide listened to indicator in music library options (31148, 31149)

Textures.xbt:
- repack content of media folder after adding new sub-menu player control fullscreen toggle icon
- repack content of media folder after adding new watched indicator icons (watched more than once)

341.DATA.xml:
- fix conditional visibility for Rip CD feature (only show for audio CDs)

overrides.xml:
- add background smartshortcuts and background browse overrides

template.xml:
- add value to widgetbackground variable for new background option
- remove background fallback of widgetBackground variable (empty value)
- add conditional visibility to watched/listened to indicator background for new option to hide these indicators

addon.xml:
- bump version to 18.0.1
- fix fanart asset

fanart.jpg:
- add new addon asset
