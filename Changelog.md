**Changes**

_New_
- add new v18 subtitle settings OSD during fullscreen video playback
- add new games section to match v18 requirements
- add new resolution select button/dialog in video player
- add player icon to now playing dialog

_Improved_
- adjust syntax, values, labels and infobools to match v18 requirements
- adjust PVR section to match v18 requirements

**Changelog v18.0.0**

_Adjust syntax, values, labels and infobools to match v18 requirements:_

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

_Adjust PVR section to match v18 requirements:_
- add views 50 to PVR windows (otherwise they're empty)
- remove deprecated views from PVR guid (everything except the EPG guide)
- remove NextChannelGroup action of guide and channel button
- hide selection buttons for windows currently open in PVR context menu

_Add new subtitle selection to match v18 requirements:_
- move subtitle settings one left on fullscreen video OSD
- rework link to new osdsubtitlesettings window

_Add new games section to match v18 requirements:_
- add GameOSD window
- add MyGames window
- add games to home menu
- add games settings category
- add game view mode and game filter dialogs
- add game widget
- add game control types
- fix gamecontroller dialog

_Add new resolution select dialog in video player to match v18 requirements:_
- add new button for resolution select dialog in video OSD

Includes.xml:
- add player icon to now playing dialog

Textures.xbt:
- update file with new resolution select icon included

addon.xml:
- bump version to 18.0.0