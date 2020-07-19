**Changes**

_New_
- add channel group switching buttons to OSD PVR channels list
- add Library Node Editor support
- add wall small view for music

_Improved_
- improve wording in skin settings
- improve watched/listened to indicator for all views/widgets
- adjust media window view positioning and size
- adjust wall and wide view for music
- improve spacing of wall low view

_Fixed_
- fix default view music and video navigation
- fix PVR channels window heading label
- fix widget icon fallback
- fix PVR OSD dialogs

**Changelog v18.4.0**

_Add new music specific wide and wall small views (viewtype523, viewtype536)_
_Rename viewtype54 to viewtype534_

strings.po:
- change 'main menu' to 'home menu', 'entry' to 'item', 'side menu' to 'submenu' and 'customisation/customise' to 'customization/customize' in all strings
- add new localizes for Library Node Editor submenu button (31400)

Textures.xbt:
- update textures file with new watched/listened to indicator files

template.xml:
- fix deprecated IsEmpty conditions
- rework watched/listened to widget indicator
- add collection indicator to widgets

Coordinates_DialogPVRChannelsOSD.xml:
- add new coordinates for channel group heading and channel group switch buttons
- rework coordinates for improved OSD guide dialog

DialogPVRChannelsOSD.xml:
- add new channel group heading, channel group switch buttons and indicators
- rework coordinates for improved OSD channels dialog

Coordinates_MyGames.xml:
- fix scrollbar height and positioning

Coordinates_MyMusicNav.xml:
- fix scrollbar height and positioning

Coordinates_MyPrograms.xml:
- fix scrollbar height and positioning

Coordinates_MyVideoNav.xml:
- fix height and positioning of scrollbars

Coordinates_Viewtype50.xml:
- add missing collection indicator

Coordinates_Viewtype51.xml:
- add missing collection indicator

Coordinates_Viewtype511.xml:
- add missing collection indicator

Coordinates_Viewtype52.xml:
- rework watched/listened to and collection indicators
- change cover art dimensions

Coordinates_Viewtype521.xml:
- rework watched/listened to and collection indicators
- change horizontal list dimensions
- change cover art dimensions

Coordinates_Viewtype522.xml:
- rework watched/listened to and collection indicators
- change horizontal list dimensions
- change cover art dimensions

Coordinates_Viewtype53.xml:
- rework watched/listened to and collection indicators
- change cover art dimensions

Coordinates_Viewtype531.xml:
- rework watched/listened to and collection indicators
- change panel dimensions
- change cover art dimensions

Coordinates_Viewtype532.xml:
- rework watched/listened to and collection indicators
- change panel dimensions
- change cover art dimensions

Coordinates_Viewtype533.xml:
- rework watched/listened to and collection indicators
- change cover art dimensions

Coordinates_Viewtype534.xml:
- rework watched/listened to and collection indicators
- change cover art dimensions

Coordinates_Viewtype54.xml:
- rework watched/listened to and collection indicators
- change cover art dimensions

Includes.xml:
- rename/add/remove includes files

MyGames.xml:
- add changed/new viewtypes

MyMusicNav.xml:
- fix default view to 'list'
- add new Library Node Editor button to submenu
- add changed/new viewtypes

MyPrograms.xml:
- add changed/new viewtypes

MyVideoNav.xml:
- remove deprecated scrollbars

MyPVRChannels.xml:
- change channel group label ID to '29'

MyVideoNav.xml:
- fix default view to 'list'
- add new Library Node Editor button to submenu

script-skinshortcuts-static.xml:
- fix deprecated IsEmpty conditions
- rework watched/listened to widget indicator
- add collection indicator to widgets

Variables.xml:
- change channel group label ID of PVR channel window heading to '29'

Viewtype50.xml:
- fix alignment of cover art (centred)

Viewtype51.xml:
- remove collection indicator from cover art
- fix alignment of cover art (centred)

Viewtype511.xml:
- remove collection indicator from cover art
- fix alignment of cover art (centred)

Viewtype52.xml:
- fix alignment of cover art (centred)
- fix visibility to only use view for movies and TV shows

Viewtype521.xml:
- fix alignment of cover art (centred)
- fix visibility to only use view for movies and TV shows

Viewtype522.xml:
- fix alignment of cover art (centred)

Viewtype53.xml:
- fix alignment of cover art (centred)

Viewtype531.xml:
- change onleft and pagecontrol for new scrollbar
- fix alignment of cover art (centred)

Viewtype532.xml:
- change onleft and pagecontrol for new scrollbar
- fix alignment of cover art (centred)

Viewtype533.xml:
- fix alignment of cover art (centred)

Viewtype534.xml:
- fix alignment of cover art (centred)

Viewtype54.xml:
- fix alignment of cover art (centred)

addon.xml:
- bump version to 18.4.0

README.md
- update readme with links to GitHub release page and OSMC Skin wiki article
