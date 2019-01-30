**Changes**

_New_
- add new v18 subtitle settings OSD during fullscreen video playback
- add new games section to match v18 requirements
- add new resolution select button/dialog in video player
- add player icon to now playing dialog
- add new dependency button in addon info dialog to match v18 requirements
- new color options (color sets, background gradients, adjustable opacity)
- add PVR channel number input dialog
- add PVR timeshift status dialog

_Improved_
- adjust syntax, values, labels and infobools to match v18 requirements
- adjust PVR section to match v18 requirements
- highlighting color now adjusts according to text color
- streamline OSD animations
- add missing adjustable plot fonts
- let favourites dialog behave like a normal window

_Fixed_
- show proper game widget title when not using skinshortcuts script
- highlighting is now more consistent
- fix current position/time remaining and current time/end time for PVR playback
- hide deprecated previous/next channel buttons in PVR playback OSD
- fix background of subtitle settings window
- fix layout of PVR playback dialogs

**Changelog v18.0.0**

_Adjust syntax, values, labels and infobools to match v18 requirements:_
- remove hyphen as none value
- remove <onclick>noop</onclick> (not needed anymore)

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


_Add new dependency button in addon info dialog to match v18 requirements:_
- add new dependencies button in addon info dialog

Addon.Browser.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

Custom_Cache_Progress.xml:
- replace colors by new color variables

Defaults.xml:
- replace colors by new color variables
- replace focus variable for button highlighting

DialogAddonInfo.xml:
- replace colors by new color variables

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
- replace colors by new color variables

DialogBusy.xml:
- replace colors by new color variables

DialogButtonMenu.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

DialogConfirm.xml:
- replace colors by new color variables

DialogContextMenu.xml:
- enable controls cycling from top to bottom and bottom to top in context menu
- replace focus variable for button highlighting

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

DialogExtendedProgressBar.xml:
- replace colors by new color variables

DialogFavourites.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- change behaviour to mimic normal window behaviour (not dialog behaviour)
- fix onup/ondown behaviour

DialogFullScreenInfo.xml:
- replace colors by new color variables
- turn title and TV channel name/number labels into fadelabels
- add PVR channel number input dialog
- add PVR timeshift status dialog
- fix current position/time remaining for PVR playback
- add PVR progress bar
- fix current time/end time for PVR playback

DialogGameControllers.xml:
- replace colors by new color variables

DialogKeyboard.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

DialogMediaSources.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

DialogMusicInfo.xml:
- replace colors by new color variables

DialogNumeric.xml:
- replace colors by new color variables

DialogPictureInfo.xml:
- replace colors by new color variables

DialogPlayerProcessInfo.xml:
- replace colors by new color variables

DialogPVRChannelGuide.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- rework window layout
- add adjustable plot font

DialogPVRChannelManager.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

DialogPVRChannelsOSD.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- rework window layout
- add adjustable plot font

DialogPVRGroupManager.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

DialogPVRGuideSearch.xml:
- replace colors by new color variables

DialogPVRInfo.xml:
- replace colors by new color variables

DialogSeekBar.xml:
- replace colors by new color variables
- fix animations
- add PVR channel number input dialog
- add PVR timeshift status dialog
- fix current position/time remaining for PVR playback
- add PVR progress bar
- fix current time/end time for PVR playback

DialogSelect.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

DialogSubtitles.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

DialogVideoInfo.xml:
- replace colors by new color variables

EventLog.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

FileBrowser.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

FileManager.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

GameOSD.xml:
- replace colors by new color variables

Home.xml:
- add new onloads
- replace colors by new color variables

Include_DialogSettings.xml:
- replace colors by new color variables

Include_Home_OSMC.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

Includes.xml:
- add player icon to now playing dialog
- rework Overlay include
- remove Custom color Overlay include
- replace colors by new color variables

Includes_Widgets.xml:
- replace colors by new color variables

LoginScreen.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

MusicOSD.xml:
- replace colors by new color variables

MusicVisualisation.xml:
- replace colors by new color variables

MyGames.xml:
- replace colors by new color variables

MyMusicNav.xml:
- replace colors by new color variables

MyMusicPlaylistEditor.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

MyPics.xml:
- replace colors by new color variables

MyPlaylist.xml:
- replace colors by new color variables

MyPrograms.xml:
- replace colors by new color variables

MyPVRChannels.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- add adjustable plot font

MyPVRGuide.xml:
- replace colors by new color variables
- remove scrollbar
- add highlighting
- add adjustable plot font

MyPVRRecordings.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- add adjustable plot font

MyPVRSearch.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- add adjustable plot font

MyPVRTimers.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

MyVideoNav.xml:
- replace colors by new color variables

MyWeather.xml:
- replace colors by new color variables

PlayerControls.xml:
- replace colors by new color variables

script-nextup-notification-NextUpInfo.xml:
- replace focus variable for button highlighting
- replace colors by new color variables

script-nextup-notification-StillWatchingInfo.xml:
- replace focus variable for button highlighting
- replace colors by new color variables

script-skin_helper_service-ColorPicker.xml:
- replace colors by new color variables

script.skinshortcuts-static-xml:
- hack game widget to show proper widget title
- replace colors by new color variables

script-skinshortcuts.xml:
- replace colors by new color variables

Settings.xml:
- replace colors by new color variables

SettingsCategory.xml:
- replace colors by new color variables
- replace focus variable for button highlighting

SettingsProfile.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- replace focus variable for button highlighting

SettingsScreenCalibration.xml:
- replace colors by new color variables

SettingsSystemInfo.xml:
- replace colors by new color variables
- replace focus variable for button highlighting

SkinSettings.xml:
- add new onloads
- replace colors by new color variables
- add new color category
- add page indicators to new color category
- rework default background image option
- remove old background and overlay color options
- add skin settings backup and restore option
- fix onup and ondown for addons submenu

SmartPlaylistEditor.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- replace focus variable for button highlighting

SmartPlaylistRule.xml:
- replace colors by new color variables

Variables.xml:
- add new color variables
- add OSMCBackgroundOverlayName variable for reworked default background image option
- remove focus variable
- add new buttonfocus variable
- replace colors by new color variables
- change PVR video player info variable
- add new PVRCHannelIconDialogOSD variable
- add new PlotDialogGuide variable
- add new PVRDescriptionDialogGuide variable

VideoFullScreen.xml:
- replace colors by new color variables
- add PVR timeshift status dialog
- fix current position/time remaining for PVR playback
- add PVR progress bar
- fix current time/end time for PVR playback

VideoOSD.xml:
- replace colors by new color variables
- add PVR channel number input dialog
- fix animations
- add PVR timeshift status dialog
- fix current position/time remaining for PVR playback
- add PVR progress bar
- fix current time/end time for PVR playback
- hide deprecated previous/next channel buttons

VideoOSDBookmarks.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

Viewtype50.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

Viewtype51.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- add adjustable plot font

Viewtype52.xml:
- replace colors by new color variables

Viewtype53.xml:
- replace colors by new color variables

Viewtype54.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

Viewtype55.xml:
- replace colors by new color variables

strings.po:
- add new localizes for reworked skin settings (31052, 31097, 31107, 31108, 31109, 31110, 31111)

Textures.xbt:
- update file with new resolution select icon included
- update file with new background gradient overlays and removed old background PNGs

overrides.xml:
- simplify game home menu entry and game widget

template.xml:
- replace colors by new color variables

addon.xml:
- bump version to 18.0.0