**Changes**

_New_
- add standard Kodi 'Menu' key functionality to access side menu in all windows
- add new Wide low info view
- add support for Up Next addon
- add playlist button to video OSD
- add 3D depth information to GUI elements

_Improved_
- make Wide low view accessible for music views
- make disabled text colour more readable
- improve widget details and window headings
- improve debug overlay
- improve overall handling of music videos
- improve playlist window
- add scrollbar to subtitle dialog

_Fixed_
- fix settings button labels for 21:9 and 4:3 modes
- fix music playlist editor window

**Changelog v18.3.0**

_add new Wide low info view and coordinates files_
_add new Up Next addon and coordinates files_
_remove deprecated Next Up addon files_
_add new custom reset skin settings confirmation dialog and coordinates files_

strings.po:
- add new localize for new Wide low info view (31392)
- change localize for Next Up successor addon Up Next (31085)
- add new explanation localize for new supported Up Next addon (31393)
- add new localize for new custom reset skin settings confirmation dialog (31394)
- rework music playlist editor and player process info dialog localizes (31008, 31011, 31156)

template.xml:
- rework widgetDetails variable

AddonBrowser.xml:
- add SidemenuMenucontrol include
- add depth include to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

Coordinates_Includes.xml:
- reorder dialog button coordinates

Coordinates_MyMusicNav.xml:
- fix Wide view scrollbar coordinates

Coordinates_MyMusicPlaylistEditor.xml:
- rework coordinates for music playlist editor window rework

Coordinates_MyVideoNav.xml:
- add coordinates for new Wide low info scrollbar

Coordinates_SettingsCategory.xml:
- add new coordinates for buttons not adjusted for different aspect ratio modes

Coordinates_DialogSubtitles.xml:
- add new coordinates for right list scrollbar

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
- add depth include to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

DialogGameControllers.xml:
- add depth include

DialogKeyboard.xml:
- add depth include

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

DialogPVRChannelsOSD.xml:
- add depth include

DialogPVRGroupManager.xml:
- add depth include

DialogPVRGuideSearch.xml:
- add depth include

DialogPVRInfo.xml:
- add depth include

DialogSeekBar.xml:
- add depth include

DialogSelect.xml:
- add depth includes
- adjust game settings animations

DialogSlider.xml:
- add depth include

DialogSubtitles.xml:
- add new right list scrollbar
- replace overlay image
- add depth include

DialogTextViewer.xml:
- add depth include

DialogVideoInfox.xml:
- add new music video information controls (similar to music info dialog)

DialogVolumeBar.xml:
- add depth include

EventLog.xml:
- add SidemenuMenucontrol include
- add depth include to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

FileBrowser.xml:
- add depth include

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

Include_DialogSettings.xml:
- update conditional visibility to hide OSD settings while Up Next notification is visible
- add depth includes

Includes_Home.xml:
- add depth include to side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

Includes_Time_NowPlaying.xml:
- rework now playing formatting
- add new information for music video playback

Includes_Windows_Dialogs.xml:
- replace FullscreenDimensions include of background images by new FullscreenOverlayDimensions include
- add depth includes to background images
- add new depth includes
- move dialog button includes from other include file

MusicOSD.xml:
- add depth include

MusicVisualisation.xml:
- adjust music information label formatting to match overall representation
- add depth include

MyGames.xml:
- add SidemenuMenucontrol include
- add depth include to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

MyMusicNav.xml:
- add SidemenuMenucontrol include
- add Wide low view
- add depth include to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

MyMusicPlaylistEditor.xml:
- rework broken music playlist editor window

MyPics.xml:
- add SidemenuMenucontrol include
- add depth include to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

MyPlaylist.xml:
- add SidemenuMenucontrol include
- add depth include to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

MyPrograms.xml:
- add SidemenuMenucontrol include
- add depth include to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

MyPVRChannels.xml:
- add SidemenuMenucontrol include
- fix onleft of scrollbar while kiosk mode is active
- add hidden label (ID 30) for improved window title
- add depth include to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

MyPVRGuide.xml:
- add SidemenuMenucontrol include
- fix visibility of submenu indicator while kiosk mode is active
- add hidden label (ID 30) for improved window title
- add depth include to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

MyPVRRecordings.xml:
- add SidemenuMenucontrol include
- add depth include to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

MyPVRSearch.xml:
- add SidemenuMenucontrol include
- fix onleft and onright of scrollbar while kiosk mode is active
- add depth include to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

MyPVRTimers.xml:
- add SidemenuMenucontrol include
- fix onleft and onright of scrollbar while kiosk mode is active
- add depth include to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

MyVideoNav.xml:
- add SidemenuMenucontrol include
- add Wide low info view
- add new scrollbar for Wide low info view
- add depth include to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

MyWeather.xml: 
- add SidemenuMenucontrol include
- add conditional visibility to hide window content, visible animation and busy dialog imitation while weather data is being loaded
- add depth include to options side menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

PlayerControls.xml:
- add depth include

Pointer.xml:
- add depth include

script-skin_helper_service-Color-Picker.xml:
- add new onload and onunload for improved debug dialog
- add depth include

script-skin_helper_service-Color-Picker.xml:
- add new onload and onunload for improved debug dialog
- change heading control to reflect currently selected colour name

script-skinshortcuts.xml:
- add new onload and onunload for improved debug dialog
- replace FullscreenDimensions include of background images by new FullscreenOverlayDimensions include
- add depth includes

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
- add depth include to settings quick-nav menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

SettingsProfile.xml:
- add depth include to settings quick-nav menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

SettingsCategory.xml:
- add depth include to settings quick-nav menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

SettingsSystemInfo.xml:
- add depth include to settings quick-nav menu
- replace FullscreenDimensions include by new FullscreenOverlayDimensions include
- move options menu slightly left to avoid it being inactively visible during 3D mode

SkinSettings.xml:
- rework Next Up supported addon button for new Up Next addon
- change window heading to use global heading variable
- change skin setting reset button to first open confirmation dialog

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

VideoFullScreen.xml:
- update conditional visibility to hide OSD elements while Up Next notification is visible
- adjust music video info dialog information to match representation in other music video windows/dialogs
- add depth include

VideoOSD.xml:
- update conditional visibility to hide OSD elements while Up Next notification is visible
- add new playlist button (like with MusicOSD)
- add depth includes

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

addon.xml:
- bump version to 18.3.0
