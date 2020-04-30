**Changes**

_New_
- add standard Kodi 'Menu' key functionality to access side menu in all windows
- add new Wide low info view
- add support for Up Next addon
- add playlist button to video OSD

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
_add new extras/Colors/colors.xml file for pre-defined ColorPicker script colour selection_

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

DialogFavourites.xml:
- add SidemenuMenucontrol include

DialogPlayerProcessInfo.xml:
- rework information label formatting

DialogSubtitles.xml:
- add new right list scrollbar

DialogVideoInfox.xml:
- add new music video information controls (similar to music info dialog)

EventLog.xml:
- add SidemenuMenucontrol include

Home.xml: 
- add SidemenuMenucontrol include

Includes.xml:
- add new SidemenuMenucontrol include
- add new include files
- adjust Media Flags animations for new Wide low info view
- adjust conditional visibility of Context/Side menu indicator include for new Wide low info view
- update conditional visibility to hide time while Up Next notification is visible
- add new onload and onunload

Include_DialogSettings.xml:
- update conditional visibility to hide OSD settings while Up Next notification is visible

Includes_Time_NowPlaying.xml:
- rework now playing formatting
- add new information for music video playback

MusicVisualisation.xml:
- adjust music information label formatting to match overall representation

MyGames.xml:
- add SidemenuMenucontrol include

MyMusicNav.xml:
- add SidemenuMenucontrol include
- add Wide low view

MyMusicPlaylistEditor.xml:
- rework broken music playlist editor window

MyPics.xml:
- add SidemenuMenucontrol include

MyPlaylist.xml:
- add SidemenuMenucontrol include

MyPrograms.xml:
- add SidemenuMenucontrol include

MyPVRChannels.xml:
- add SidemenuMenucontrol include
- fix onleft of scrollbar while kiosk mode is active
- add hidden label (ID 30) for improved window title

MyPVRGuide.xml:
- add SidemenuMenucontrol include
- fix visibility of submenu indicator while kiosk mode is active
- add hidden label (ID 30) for improved window title

MyPVRRecordings.xml:
- add SidemenuMenucontrol include

MyPVRSearch.xml:
- add SidemenuMenucontrol include
- fix onleft and onright of scrollbar while kiosk mode is active

MyPVRTimers.xml:
- add SidemenuMenucontrol include
- fix onleft and onright of scrollbar while kiosk mode is active

MyVideoNav.xml:
- add SidemenuMenucontrol include
- add Wide low info view
- add new scrollbar for Wide low info view

MyWeather.xml: 
- add SidemenuMenucontrol include
- add conditional visibility to hide window content, visible animation and busy dialog imitation while weather data is being loaded

script-skin_helper_service-Color-Picker.xml:
- add new onload and onunload for improved debug dialog

script-skinshortcuts.xml:
- add new onload and onunload for improved debug dialog

script-skin_helper_service-Color-Picker.xml:
- add new onload and onunload for improved debug dialog
- change heading control to reflect currently selected colour name

script-upnext-stillwatching-simple.xml:
- add new onload and onunload for improved debug dialog

script-upnext-stillwatching.xml:
- add new onload and onunload for improved debug dialog

script-upnext-upnext-simple.xml:
- add new onload and onunload for improved debug dialog

script-upnext-upnext.xml:
- add new onload and onunload for improved debug dialog

SettingsCategory.xml: 
- add menucontrol
- adjust buttons not adapting to different aspect ratio modes

SkinSettings.xml:
- rework Next Up supported addon button for new Up Next addon
- change window heading to use global heading variable
- change skin setting reset button to first open confirmation dialog

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

VideoOSD.xml:
- update conditional visibility to hide OSD elements while Up Next notification is visible
- add new playlist button (like with MusicOSD)

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
