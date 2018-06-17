- add variable "VideoResolution" (output resolution values except 4K that should be converted to 2160)
- add variable "VideoCodec" (translation of Kodi's codec IDs into known codec names)
- add variable "3DMode" (either use "ListItem.IsStereoscopic" - which just works after a first playback mostly - or file/path name syntax - based on Kodi wiki suggestions - to show a 3D label)
- add variables "MusicNextPlaying1", "MusicNextPlaying2" and "MusicNextPlaying3" (one for each line required in the next playing dialog in MusicVisualisation.xml, not all lines are always required -> variables needed)
- add variables "SEplaying", "SElist" and "SEContainer" needed for "SxxExx" representation in list view and in widget titles (add line to show only episode title when ListItem.Episode contains the character "s" - for series specials)
- adjust "Label1" variable to show titles, if present, and show episode titles as "SxxExx [separator] episode title"
- replace "Aired on" by a LOCALIZE showing "First air date" (replacing only English line)
- add variables "VideoPlayerAudioChannels", "VideoPlayerAudioCodec", "VideoPlayerCodec"
- always use uppercase for "Sx" format of specials in relevant variables
- add variable "SEListView" for use in episode list view
- replace "Now" and "Next" in PVR full screen playback info title variable by localizes
- change "mediaImages" variable to react to new skin setting
 
Viewtype51.xml:
- adjust text box height of plots shown when selecting a TV show episode in list view (to avoid collision with new MediaFlags representation)
- replace separator " / " by point separator (adapting the separator used between season and episode: "season x [separator] episode x" to the one used in list view and episode widget titles)
- use variable "SEListView" in episode list view to only show "Episode Sx" when selecting a special
 
Viewtype52.xml, Viewtype53.xml, Viewtype55.xml:
- use variable "Label1" for titles
- adjust width of title fadelabel to match width of scrollbar under wide list view
- adjust width of details fadelabel to avoid collision with media flags (matching the width of the details fadelabel under Viewtype53.xml)
 
Viewtype54.xml:
- use fadelabel for artist/album title under album cover in music list view (enable scrolling of long titles)
 
Viewtype55.xml:
- move thumbs in wall view for music and programs slightly down and decrease spacing between them to correct spacing with system time and window headings
 
string.po:
- add two new localizes for new skin settings buttons (#31100 and #31101)
- add new localize for new skin settings button (#31102)
- add new localize for new skin settings button (#31103)
 
Textures.xbt:
- repack content of media folder
 
template.xml:
- add/adjust variable conditions needed for "SxxExx" representation in in widget titles when using script-skinshortcuts (add line to show only episode title when ListItem.Episode contains the character "s" - for series specials)
- adjust episode widget title to always use uppercase for "Sx" format of specials
- replace "Loading…" by a LOCALIZE showing "Please wait…" (replacing only English line)
 
addon.xml:
- bump version to 17.0.4

**Changes v18.0.0**

_New_
- add new v18 subtitle settings OSD during fullscreen video playback
- add games section

_Improved_
- adjust syntax, values, labels and infobools to match v18 requirements

**Changelog v18.0.0**

- remove hyphen as none value
- remove <onclick>noop</onclick> (not needed anymore)

DialogAddonSettings.xml
- change grouplist id="9" to id="3"
- change button id="13" to id="10"
- change grouplist id="2" to id="5"
- change button id="3" to id="7"
- change radio button id="4" to id="8"
- change spincontrolex id="5" to id="9"
- change image id="6" to id="11"
- add edit id="12"
- change sliderex id="8" to id="13"
- change label id="7" to id="14"
- change button id="10" to id="28"
- change button id="11" to id="29"
- change button id="12" to id="30"

DialogContextMenu.xml:
- enable controls cycling from top to bottom and bottom to top in context menu

- rename DialogPVRGuideOSD.xml to DialogPVRChannelGuide.xml
- replace infolabel ListItem.ChannelNumber by ListItem.ChannelNumberLabel
- replace infolabel VideoPlayer.ChannelNumber by VideoPlayer.ChannelNumberLabel
- replace duration labels by new duration variable
- replace IsEmpty() by String.IsEmpty()
- replace StringCompare() by String.IsEqual()
- replace IntegerGreaterThan() by Integer.IsGreater()
- add all/watched/unwatched toggle button to PVR recordings
- replace localize values under the skin settings section with new values (Background label)
- replace Player.Recording infolabel by PVR.IsRecordingPlayingChannel
- replace PlayerControl(Record) command by PVR.ToggleRecordPlayingChannel
- replace Player.CanRecord infolabel by PVR.CanRecordPlayingChannel
- replace Movies, TV Show and Music home menu links
- add views 50 to PVR windows (otherwise they're empty)
- remove deprecated views from PVR guid (everything except the EPG guide)
- remove NextChannelGroup action of guide and channel button
- hide selection buttons for windows currently open in PVR context menu
- move subtitle settings one left on fullscreen video OSD
- rework link to new osdsubtitlesettings window
- add GameOSD window
- add MyGames window
- add games to home menu
- add games settings category
- add game view mode and game filter dialogs
- add game widget
- add game control types
- fix gamecontroller dialog

addon.xml:
- bump version to 18.0.0