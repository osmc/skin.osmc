**Changes**

_New_
- add standard Kodi 'Menu' key functionality to access side menu in all windows
- add album duration to album music library view
- add new Wide low info view
- add support for Up Next addon

_Improved_
- make Wide low view accessible for music views
- make disabled text colour more readable

_Fixed_
- fix settings button labels for 21:9 and 4:3 modes

**Changelog v18.3.0**

_add new Wide low info view and coordinates files_
_add new Up Next addon and coordinates files_
_ remove deprecated Next Up addon files_

strings.po:
- add new localizes for new Wide low info view (31392)
- change localize for Next Up successor addon Up Next (31085)
- add new explanation localize for new supported Up Next addon (31393)

AddonBrowser.xml:
- add SidemenuMenucontrol include

Coordinates_MyMusicNav.xml:
- fix Wide view scollbar coordinates

Coordinates_MyVideoNav.xml:
- add coordinates for new Wide low info scollbar

Coordinates_SettingsCategory.xml:
- add new coordinates for buttons not adjusted for different aspect ratio modes

DialogFavourites.xml:
- add SidemenuMenucontrol include

EventLog.xml:
- add SidemenuMenucontrol include

Home.xml: 
- add SidemenuMenucontrol include

Includes.xml:
- add new SidemenuMenucontrol include
- add new include files
- adjust Media Flags animations for new Wide low info view
- add total time of albums to Media Flags duration
- adjust conditional visibility of Context/Side menu indicator include for new Wide low info view
- update conditional visibility to hide time while Up Next notification is visible

Include_DialogSettings.xml:
- update conditional visibility to hide OSD settings while Up Next notification is visible

MyGames.xml:
- add SidemenuMenucontrol include

MyMusicNav.xml:
- add SidemenuMenucontrol include
- add Wide low view

MyPics.xml:
- add SidemenuMenucontrol include

MyPlaylist.xml:
- add SidemenuMenucontrol include

MyPrograms.xml:
- add SidemenuMenucontrol include

MyPVRChannels.xml:
- add SidemenuMenucontrol include
- fix onleft of scrollbar while kiosk mode is active

MyPVRGuide.xml:
- add SidemenuMenucontrol include
- fix visibility of submenu indicator while kiosk mode is active

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

SettingsCategory.xml: 
- add menucontrol
- adjust buttons not adapting to different aspect ratio modes

SkinSettings.xml:
- rework Next Up supported addon button for new Up Next addon

Variables.xml:
- adjust colour values of DisabledColor variable
- adjust VideoPlayerTitle variable to show year of movies and TV shows in video player info dialog title
- add new UpNextTitle variable
- rework addon-upnext variable for new Up Next addon
- add new explanation text for Up Next addon to SkinSettingsExplanation variable

VideoFullScreen.xml:
- update conditional visibility to hide OSD elements while Up Next notification is visible

VideoOSD.xml:
- update conditional visibility to hide OSD elements while Up Next notification is visible

Viewtype521.xml:
- enable view in music library sections

Viewtype54.xml:
- add visibility condition to hide user rating label, if disabled in skin settings

Textures.xbt:
- update textures file with new button highlight textures

addon.xml:
- bump version to 18.3.0
