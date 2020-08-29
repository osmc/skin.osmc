**Changes**

_New_
- add channel group switching buttons to OSD PVR channels list
- add Library Node Editor support
- add wall small view for music
- add automatic masking for scope skin version
- add second dialog page to music, PVR and addon info dialog

_Improved_
- improve wording in skin settings
- improve watched/listened to indicator for all views/widgets
- adjust media window view positioning and size
- adjust wall and wide view for music
- improve spacing of wall low view
- improve PVR descriptions
- rework now playing information and fullscreen music playback information
- add missing detail labels to PVR and music info dialogs

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
- add new localize for Library Node Editor submenu button (31400)
- add new localizes for automatic masking setting (31401, 31402, 31403)
- adjust localize of plot font size setting (31326)
- add new localize for new addon info dialog label (31404)
- add new localize for fullscreen live TV playback OSD info dialog (31171)
- add new localizes for new recommended/supported addons (31405, 31406, 31407, 31408)

Textures.xbt:
- update textures file with new watched/listened to indicator files
- update textures file with new automatic aspect ratio OSD control icon

template.xml:
- fix deprecated IsEmpty conditions
- rework watched/listened to widget indicator
- add collection indicator to widgets

Coordinates_Custom_DialogMasking.xml:
- adjust coordinates for new OSD masking aspect ratio dialog layout

Coordinates_DialogPVRChannelsOSD.xml:
- add new coordinates for channel group heading and channel group switch buttons
- rework coordinates for improved OSD guide dialog

Custom_DialogMasking.xml:
- change heading localize
- rework buttons options to match skin settings masking aspect ratio setting layout

Coordinates_DialogAddonInfo.xml:
- adjust height if details group list and description textbox

Coordinates_DialogMusicInfo.xml:
- adjust height if details group list and description textbox
- remove deprecated coordinate includes

Coordinates_DialogPVRInfo.xml:
- adjust height if details group list and plot textbox

Coordinates_MyGames.xml:
- fix scrollbar height and positioning

Coordinates_MyMusicNav.xml:
- fix scrollbar height and positioning

Coordinates_MyPrograms.xml:
- fix scrollbar height and positioning

Coordinates_MyPVRGuide.xml:
- add fade animation to non-focus recording and timer images

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

DialogAddonInfo.xml:
- add new onload and unload for second info dialog page
- add new addon origin detail label
- rework description textbox for second info dialog page
- add new extended info button for second info dialog page

DialogMusicInfo.xml:
- add new onload and unload for second info dialog page
- add new filename and path label
- add missing detail labels
- replace type label localize
- rework description textbox for second info dialog page
- add new extended info button for second info dialog page

DialogPVRChannelsOSD.xml:
- add new channel group heading, channel group switch buttons and indicators
- rework coordinates for improved OSD channels dialog

DialogPVRInfo.xml:
- add new onload and unload for second info dialog page
- fix heading to show PVR show title
- rework plot textbox for second info dialog page
- add new extended info button for second info dialog page
- change Channel Name label to match representation in other places
- add missing detail labels

DialogVideoInfo.xml:
- rework visibility conditions, onup and usealttexture for new movie set information page
- add new movie set poster image
- rework order of detail labels
- add new set detail label
- rework plot textbox for second info dialog page
- add new extended info button for second info dialog page

Home.xml:
- rework RSS feed with animation for masking

Includes.xml:
- rename/add/remove includes files
- rework masking animations for new automatic masking
- change onload for new info dialog settings

Includes_Time_NowPlaying.xml:
- rework now playing information completely (more specifically for all player media types)

MusicVisualisation.xml:
- rework fullscreen music playback information

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

SettingsScreenCalibration.xml:
- rework masking animations for new automatic masking

SkinSettings.xml:
- add new automatic masking setting
- change info dialog setting for new second info dialog pages
- add ColorPicker and Library Node Editor to recommended/supported addons

Variables.xml:
- change channel group label ID of PVR channel window heading to '29'
- simplify PVRDescription and PVRDescriptionDialogGuide variables and add genre info label
- add disc number info label to MusicInfoLabel variable
- rework addonInformation variable
- rework VideoPlayerChannelNumber variable to match representation in other places

Variables_SkinSettings.xml:
- add new automatic masking setting explanation variable
- rework SkinSettingsExplanation variable for changed info dialog setting
- add new addon-skinhelpercolorpicker and addon-librarynodeeditor variables for added recommended/supported addons
- rework SkinSettingsExplanation variable for added recommended/supported addons explanations

VideoFullScreen.xml:
- rework masking animations for new automatic masking
- replace label of Live TV next information by new localize

VideoOSD.xml:
- change conditional visibility and add new icon to masking control button for new automatic masking aspect ratio setting

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
