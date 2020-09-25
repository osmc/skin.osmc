**Changes**

_New_
- add channel group switching buttons to OSD PVR channels list
- add Library Node Editor support
- new square versions of existing views for video addons and music
- add automatic masking for scope skin version
- add second dialog page to music, PVR and addon info dialog
- add setting to force a specific view for video addons

_Improved_
- improve wording in skin settings
- improve watched/listened to indicator for all views/widgets
- adjust media window view positioning and size
- adjust wall and wide view for music
- improve spacing of wall low view
- improve PVR descriptions
- rework now playing information and fullscreen music playback information
- add missing detail labels to PVR and music info dialogs
- show TV show episode thumb in video info dialog
- use the more extended list view for more content types (addons, games, files and pictures)
- improve second label of more extended list view
- add wide view support to games and programs
- harmonize non-focus animations
- improve scrollbar size relative to their controls

_Fixed_
- fix default view music and video navigation
- fix PVR channels window heading label
- fix widget icon fallback
- fix PVR OSD dialogs

**Changelog v18.4.0**

_Rename viewtype54 to viewtype534_
_Rename viewtype536 to viewtype537_
_Add new square versions of existing views for music and video addons (viewtype523, viewtype524, viewtype525, viewtype536, viewtype537, viewtype538, viewtype539)_

strings.po:
- change 'main menu' to 'home menu', 'entry' to 'item', 'side menu' to 'submenu' and 'customisation/customise' to 'customization/customize' in all strings
- add new localize for Library Node Editor submenu button (31400)
- add new localizes for automatic masking setting (31401, 31402, 31403)
- adjust localize of plot font size setting (31326)
- add new localize for new addon info dialog label (31404)
- add new localize for fullscreen live TV playback OSD info dialog (31171)
- add new localizes for new recommended/supported addons (31405, 31406, 31407, 31408)
- add new localizes for new video addons default view setting (31409, 31410, 31411, 31412)

Textures.xbt:
- update textures file with new watched/listened to indicator files
- update textures file with new automatic aspect ratio OSD control icon

template.xml:
- fix deprecated IsEmpty conditions
- rework watched/listened to widget indicator
- add collection indicator to widgets

AddonBrowser.xml:
- replace visible change fade animation by VisibleFadeAnimation include

Coordinates_AddonBrowser.xml:
- add addon version to second row list label
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- decrease scrollbar height

Coordinates_Custom_DialogMasking.xml:
- adjust coordinates for new OSD masking aspect ratio dialog layout

Coordinates_DialogAddonInfo.xml:
- adjust height if details group list and description textbox

Coordinates_DialogButtonMenu.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes

Coordinates_DialogFavourites.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- decrease scrollbar height

Coordinates_DialogGameControllers.xml:
- decrease scrollbar height

Coordinates_DialogKeyboard.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes

Coordinates_DialogMediaSource.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes

Coordinates_DialogMusicInfo.xml:
- adjust height if details group list and description textbox
- remove deprecated coordinate includes

Coordinates_DialogPictureInfo.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- decrease scrollbar height

Coordinates_DialogPVRChannelGuide.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- decrease scrollbar height

Coordinates_DialogPVRChannelManager.xml:
- fix ActiveChannel fade animations
- add NonFocusFadeAnimation includes to focusedlayout
- decrease scrollbar height

Coordinates_DialogPVRChannelsOSD.xml:
- add new coordinates for channel group heading and channel group switch buttons
- rework coordinates for improved OSD guide dialog
- remove unnecessary fade animations
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- decrease scrollbar height

Coordinates_DialogPVRGroupManager.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- decrease scrollbar height

Coordinates_DialogPVRInfo.xml:
- adjust height if details group list and plot textbox

Coordinates_DialogSelect.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- fix icon fade animations
- decrease scrollbar height

Coordinates_DialogSubtitles.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- fix icon fade animations
- decrease scrollbar height

Coordinates_DialogTextViewer.xml:
- decrease scrollbar height

Coordinates_DialogVideoInfo.xml:
- decrease scrollbar height

Coordinates_EventLog.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- decrease scrollbar height

Coordinates_FileBrowser.xml:
- fix icon fade animations
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- decrease scrollbar height

Coordinates_FileManager.xml:
- fix label width when label2 is not empty
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- decrease scrollbar height

Coordinates_Home.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes

Coordinates_LoginScreen.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes

Coordinates_MyGames.xml:
- decrease scrollbar height and fix positioning
- add new coordinates includes for new wide scrollbar

Coordinates_MyMusicNav.xml:
- decrease scrollbar height and fix positioning

Coordinates_MyMusicPlaylistEditor.xml:
- add NonFocusFadeAnimation includes to focusedlayout
- remove unnecessary non-focus controls
- decrease scrollbar height

Coordinates_MyPics.xml:
- decrease scrollbar height

Coordinates_MyPlaylist.xml:
- decrease scrollbar height

Coordinates_MyPrograms.xml:
- decrease scrollbar height and fix positioning
- add new coordinates includes for new wide scrollbar

Coordinates_MyPVRChannels.xml:
- fix placing and width of label controls
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- decrease scrollbar height

Coordinates_MyPVRGuide.xml:
- add fade animation to non-focus recording and timer images
- add NonFocusFadeAnimation includes to focusedlayout
- replace icon fade animations by new NonFocusImageFadeAnimation include
- decrease scrollbar height

Coordinates_MyPVRRecordings.xml:
- fix width of 4:3 label controls
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- decrease scrollbar height

Coordinates_MyPVRSearch.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- replace icon fade animations by new NonFocusImageFadeAnimation include
- decrease scrollbar height

Coordinates_MyPVRTimers.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- replace icon fade animations by new NonFocusImageFadeAnimation include
- decrease scrollbar height

Coordinates_MyVideoNav.xml:
- decrease scrollbar height

Coordinates_script-skinshortcuts.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- decrease scrollbar height

Coordinates_SettingsProfile.xml:
- fix width of label and image controls
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes
- replace icon fade animations by new NonFocusImageFadeAnimation include

Coordinates_SmartPlaylistEditor.xml:
- place focusedlayout items into a group control and add NonFocusFadeAnimation includes

Coordinates_VideoOSDBookmarks.xml:
- add NonFocusFadeAnimation includes to focusedlayout

Coordinates_MyVideoNav.xml:
- fix height and positioning of scrollbars

Coordinates_Viewtype50.xml:
- add missing collection indicator
- add NonFocusFadeAnimation includes to focusedlayout
- replace icon fade animations by new NonFocusImageFadeAnimation include

Coordinates_Viewtype51.xml:
- add missing collection indicator
- add NonFocusFadeAnimation includes to focusedlayout
- replace icon fade animations by new NonFocusImageFadeAnimation include

Coordinates_Viewtype511.xml:
- add missing collection indicator
- add NonFocusFadeAnimation includes to focusedlayout
- replace icon fade animations by new NonFocusImageFadeAnimation include

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

Coordinates_Viewtype523.xml:
- add new addons, games and videos images includes

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

Coordinates_Viewtype536.xml:
- rework coordinates includes for new video addons and music views

Custom_DialogMasking.xml:
- change heading localize
- rework buttons options to match skin settings masking aspect ratio setting layout

DialogAddonInfo.xml:
- add new onload and unload for second info dialog page
- add new addon origin detail label
- rework description textbox for second info dialog page
- add new extended info button for second info dialog page

DialogFavourites.xml:
- replace visible change fade animation by VisibleFadeAnimation include

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

EventLog.xml:
- replace visible change fade animation by VisibleFadeAnimation include

Home.xml:
- rework RSS feed with animation for masking

Includes.xml:
- rename/add/remove includes files
- rework masking animations for new automatic masking
- change onload for new info dialog settings
- change onload for new video addons default view setting
- add new DefaultView include
- replace visible change fade animation by VisibleFadeAnimation include
- update SubmenuIndicator conditional visibilities with new viewtypes

Includes_Home.xml:
- replace visible change fade animation by VisibleFadeAnimation include

Includes_Time_NowPlaying.xml:
- rework now playing information completely (more specifically for all player media types)
- rework animations for new video addons and music views

Includes_Windows_Dialogs.xml:
- replace VisibleFadeAnimation include animations by VisibleChange animation
- add new NonFocusFadeAnimation include
- replace visible change fade animation by VisibleFadeAnimation include
- add new NonFocusImageFadeAnimation include

LoginScreen.xml:
- replace visible change fade animation by VisibleFadeAnimation include

MusicVisualisation.xml:
- rework fullscreen music playback information

MyGames.xml:
- add changed/new viewtypes
- replace visible change fade animation by VisibleFadeAnimation include

MyMusicNav.xml:
- fix default view to 'list'
- add new Library Node Editor button to submenu
- add changed/new viewtypes
- replace visible change fade animation by VisibleFadeAnimation include

MyPics.xml:
- add new view
- replace visible change fade animation by VisibleFadeAnimation include

MyPlaylist.xml:
- replace visible change fade animation by VisibleFadeAnimation include


MyPrograms.xml:
- add changed/new viewtypes
- replace visible change fade animation by VisibleFadeAnimation include

MyVideoNav.xml:
- remove deprecated scrollbars
- add new views

MyPVRChannels.xml:
- change channel group label ID to '29'
- replace visible change fade animation by VisibleFadeAnimation include

MyPVRGuide.xml:
- replace visible change fade animation by VisibleFadeAnimation include

MyPVRRecordings.xml:
- replace visible change fade animation by VisibleFadeAnimation include

MyPVRSearch.xml:
- replace visible change fade animation by VisibleFadeAnimation include

MyPVRTimers.xml:
- replace visible change fade animation by VisibleFadeAnimation include

MyVideoNav.xml:
- fix default view to 'list'
- add new Library Node Editor button to submenu
- replace visible change fade animation by VisibleFadeAnimation include

MyWeather.xml:
- replace visible change fade animation by VisibleFadeAnimation include

script-skinshortcuts.xml:
- remove unnecessary non-focus fade animation

script-skinshortcuts-static.xml:
- fix deprecated IsEmpty conditions
- rework watched/listened to widget indicator
- add collection indicator to widgets

Settings.xml:
- fix non-focus fade animations

SettingsCategory.xml:
- replace visible change fade animation by VisibleFadeAnimation include

SettingsProfile.xml:
- replace visible change fade animation by VisibleFadeAnimation include

SettingsScreenCalibration.xml:
- rework masking animations for new automatic masking

SettingsSystemInfo.xml:
- replace visible change fade animation by VisibleFadeAnimation include

SkinSettings.xml:
- add new automatic masking setting
- change info dialog setting for new second info dialog pages
- add ColorPicker and Library Node Editor to recommended/supported addons
- add new setting to force a specific view for video addons

Variables.xml:
- change channel group label ID of PVR channel window heading to '29'
- simplify PVRDescription and PVRDescriptionDialogGuide variables and add genre info label
- add disc number info label to MusicInfoLabel variable
- rework addonInformation variable
- rework VideoPlayerChannelNumber variable to match representation in other places
- add TV show poster condition to mediaImages variable
- replace TV show and season poster conditions by DBTYPE episode icon art in VideoInfoImage variable
- add new videos values to ContentType variable
- add new episodes, videos, addons, images and files values to as well as remove deprecated values from Label2 variable
- remove deprecated Label2-episodes variable

Variables_SkinSettings.xml:
- add new automatic masking setting explanation variable
- rework SkinSettingsExplanation variable for changed info dialog setting
- add new addon-skinhelpercolorpicker and addon-librarynodeeditor variables for added recommended/supported addons
- rework SkinSettingsExplanation variable for added recommended/supported addons explanations
- rework SkinSettingsExplanation variable for added video addons force view settings explanations

VideoFullScreen.xml:
- rework masking animations for new automatic masking
- replace label of Live TV next information by new localize

VideoOSD.xml:
- change conditional visibility and add new icon to masking control button for new automatic masking aspect ratio setting

Viewtype50.xml:
- fix alignment of cover art (centred)
- rework list visibility condition to be shown for less content types

Viewtype51.xml:
- remove collection indicator from cover art
- fix alignment of cover art (centred)
- rework list visibility condition to be shown for more content types
- add DefaultView include

Viewtype511.xml:
- remove collection indicator from cover art
- fix alignment of cover art (centred)
- rework list visibility condition to be shown for more content types
- add DefaultView include

Viewtype52.xml:
- fix alignment of cover art (centred)
- fix visibility to only use view for movies and TV shows
- remove unnecessary non-focus fade animation

Viewtype521.xml:
- fix alignment of cover art (centred)
- fix visibility to only use view for movies and TV shows
- remove unnecessary non-focus fade animation

Viewtype522.xml:
- fix alignment of cover art (centred)

Viewtype523.xml:
- rework visibility conditions with more content types
- add DefaultView include
- remove unnecessary non-focus fade animation

Viewtype524.xml:
- remove unnecessary non-focus fade animation

Viewtype53.xml:
- fix alignment of cover art (centred)
- remove unnecessary non-focus fade animation

Viewtype531.xml:
- change onleft and pagecontrol for new scrollbar
- fix alignment of cover art (centred)

Viewtype532.xml:
- change onleft and pagecontrol for new scrollbar
- fix alignment of cover art (centred)
- remove unnecessary non-focus fade animation

Viewtype533.xml:
- fix alignment of cover art (centred)

Viewtype534.xml:
- fix alignment of cover art (centred)
- remove unnecessary non-focus fade animation

Viewtype535.xml:
- rework visibility conditions with more content types
- add DefaultView include
- remove unnecessary non-focus fade animation

Viewtype537.xml:
- rework visibility conditions with more content types
- add DefaultView include
- remove unnecessary non-focus fade animation

addon.xml:
- bump version to 18.4.0

README.md
- update readme with links to GitHub release page and OSMC Skin wiki article
