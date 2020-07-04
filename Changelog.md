**Changes**

_New_
- add channel group switching buttons to OSD PVR channels list
- add Library Node Editor support

_Improved_
- improve wording in skin settings

_Fixed_
- fix default view music and video navigation
- fix PVR channels window heading label
- fix widget icon fallback

**Changelog v18.4.0**

strings.po:
- change 'main menu' to 'home menu', 'entry' to 'item', 'side menu' to 'submenu' and 'customisation/customise' to 'customization/customize' in all strings
- add new localizes for Library Node Editor submenu button (31400)

template.xml:
- fix deprecated IsEmpty conditions

Coordinates_DialogPVRChannelsOSD.xml:
- add new coordinates for channel group heading and channel group switch buttons

DialogPVRChannelsOSD.xml:
- add new channel group heading, channel group switch buttons and indicators

MyMusicNav.xml:
- fix default view to 'list'
- add new Library Node Editor button to submenu

MyPVRChannels.xml:
- change channel group label ID to '29'

MyVideoNav.xml:
- fix default view to 'list'
- add new Library Node Editor button to submenu

script-skinshortcuts-static.xml:
- fix deprecated IsEmpty conditions

Variables.xml:
- change channel group label ID of PVR channel window heading to '29'

addon.xml:
- bump version to 18.4.0

README.md
- update readme with links to GitHub release page and OSMC Skin wiki article
