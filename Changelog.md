**Changes**

_New_
- add option to adjust dim factor of unfocused art 
- add option for additional text highlight

_Improved_
- add more weather information to weather window
- refine music icons
- remove watched status for music items (in views and widgets)
- adjust representation of object based audio codec tags

_Fixed_
- fix scrollbar in music navigation
- fix item widths in various windows
- fix weather window
- fix focused items in addon list view (e.g. YouTube)

**Changelog v17.0.5**

AddonBrowser.xml:
- add underline highlight to focusedlayout

Defaults.xml:
- add focus textures with colordiffuse variable

DialogAudioDSPManager:
- add underline highlight to focusedlayout

DialogButtonMenu.xml:
- add underline highlight to focusedlayout

DialogContextMenu.xml:
- add focus texture with colordiffuse variable

DialogFavourites:
- add underline highlight to focusedlayout

DialogFullScreenInfo.xml:
- override button highlight to never show

DialogMediaSource.xml:
- add underline highlight to focusedlayout

DialogPVRChannelGuide:
- add underline highlight to focusedlayout

DialogPVRChannelManager:
- add underline highlight to focusedlayout

DialogPVRChannelsOSD:
- add underline highlight to focusedlayout

DialogPVRGroupManager:
- add underline highlight to focusedlayout

DialogSelect:
- add underline highlight to focusedlayout

DialogSubtitles:
- add underline highlight to focusedlayout

FileBrowser:
- add underline highlight to focusedlayout

FileManager:
- add underline highlight to focusedlayout

Font.xml:
- add new Font73 with bold style

Home.xml:
- add onload to set NFDimOpac skin string to 100

Include_Home_OSMC.xml:
- add underline highlight to focusedlayout

LoginScreen.xml:
- add underline highlight to focusedlayout

MusicOSD.xml:
- make visualization settings buttons conditionally visible

MusicVisualisation.xml:
- fix width of next playing fadelabels

MyMusicNav.xml:
- fix conditional visibility of scrollbar

MyMusicPlaylistEditor.xml:
- add underline highlight to focusedlayout
- add focus textures with colordiffuse variable to buttons

MyPVRChannels.xml:
- add underline highlight to focusedlayout

MyPVRRecordings.xml:
- add underline highlight to focusedlayout

MyPVRSearch.xml
- add underline highlight to focusedlayout

MyPVRTimers.xml
- add underline highlight to focusedlayout

MyWeather.xml:
- fix day labels
- match forcast to correct day
- replace localize for "now" with translatable one
- add more weather information (humidity/precepitation, sunrise/sunset)

script-skinshortcuts-static.xml:
- replace DiffusePosterNF with variable

script-skinshortcuts.xml:
- add underline highlight to focusedlayout

Settings.xml:
- change togglebutton layout (increase button hight, reduce item gap)

SettingsCategory.xml:
- add focus textures with colordiffuse variable to buttons

SettingsProfile.xml:
- add underline highlight to focusedlayout
- add focus textures with colordiffuse variable to buttons

SettingsSystemInfo.xml:
- fix button width
- add focus textures with colordiffuse variable to buttons

SkinSettings.xml:
- rewrite window to accomodate highlighting and immitate behaviour of other settings windows

SmartPlaylistEditor.xml:
- add underline highlight to focusedlayout
- add focus textures with colordiffuse variable to buttons

Variables.xml:
- add DiffusePosterNF variable (used for new cover art dim option)
- add focus variables (used for new highlighting option)
- cleanup mediaImages variable
- remove now unused Day variables
- adjust StatusOverlay/StatusOverlayWide variables to hide watched status for music

Viewtype50.xml:
- add underline highlight to focusedlayout
- use new Font73 for focused label
- remove bold style from focused label

Viewtype51.xml:
- add underline highlight to focusedlayout

Viewtype52.xml:
- replace DiffusePosterNF with variable

Viewtype53.xml:
- replace DiffusePosterNF with variable

Viewtype54.xml:
- fix width of Artist info fadelabel
- add underline highlight to focusedlayout

Viewtype55.xml:
- replace DiffusePosterNF with variable
- show title in wall view for addons/games as well

defaults.xml:
- remove DiffusePosterNF color

strings.po:
- add new localizes for new skin settings buttons (#31104 and #31105)

Textures.xbt:
- repack content of media folder after adding new focus textures
- repack content of media folder after adding new music icons

template.xml:
- replace DiffusePosterNF with variable

addon.xml:
- bump version to 17.0.5