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
- add welcome dialog on non-OSMC devices
- add director button to video info dialog
- add new views (wide low, wall small, wall low, wall info, list info)
- add new sub-menu indicator icon
- add "Random TV shows" widget as new standard for TV shows home menu entry
- add new dialog navigation indicators
- add ratings toggle for IMDb, Metacritic, Rotten Tomatoes and TVDb
- add new video player OSD settings (show OSD after beginning of playback and before end of playback)

_Improved_
- adjust syntax, values, labels and infobools to match v18 requirements
- adjust PVR section to match v18 requirements
- highlighting color now adjusts according to text color
- streamline OSD animations
- add missing adjustable plot fonts
- let favourites dialog behave like a normal window
- add file path and name to refresh button in video info dialog
- add song/album year to music player
- add wide list as music view
- add music OSD album art size switch
- adjust widget headings to always show and adjust animations to match widget animations
- add option to change widget labels

_Fixed_
- show proper game widget title when not using skinshortcuts script
- highlighting is now more consistent
- fix current position/time remaining and current time/end time for PVR playback
- hide deprecated previous/next channel buttons in PVR playback OSD
- fix background of subtitle settings window
- fix layout of PVR playback dialogs
- fix dialog list navigation
- change font size of media tags to prevent overlap with titles/details
- only offer rip CD feature when an audio CD is present

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
- add onload to show welcome screen after installing the skin from zip
- add submenu indicator
- add onloads for new OSD settings

Custom_Backup.xml:
- add new dialog prompt when skin helper service skin backup script is disabled

Custom_Cache_Progress.xml:
- replace colors by new color variables

Custom_Customization.xml:
- add new dialog prompt when skin helper script is disabled

Custom_Disabled_Add-on.xml:
- add new dialog prompt when supported skin add-ons are disabled

Custom_Welcome.xml
- add new Welcome dialog for non-OSMC devices

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
- fix ondown, onup and onleft of lists
- add new navigation indicator

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
- add submenu indicator

DialogFullScreenInfo.xml:
- replace colors by new color variables
- turn title and TV channel name/number labels into fadelabels
- add PVR channel number input dialog
- add PVR timeshift status dialog
- fix current position/time remaining for PVR playback
- add PVR progress bar
- fix current time/end time for PVR playback
- remove info dialog

DialogGameControllers.xml:
- replace colors by new color variables
- fix ondown and onup of lists
- add new navigation indicator

DialogKeyboard.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists

DialogMediaSources.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- fix ondown and onleft of lists

DialogMusicInfo.xml:
- replace colors by new color variables
- remove unused tracks/discography list (id 50)

DialogNumeric.xml:
- replace colors by new color variables

DialogPictureInfo.xml:
- replace colors by new color variables
- fix ondown and onup of the list
- add missing hightlighting
- add new navigation indicator

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
- fix ondown, onup, onleft and onright of lists
- add new navigation indicator

DialogPVRChannelsOSD.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- rework window layout
- add adjustable plot font

DialogPVRGroupManager.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- fix ondown, onup, onleft and onright of lists
- add new navigation indicator

DialogPVRGuideSearch.xml:
- replace colors by new color variables
- fix onleft and onright of lists

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
- remove PVR channel number input dialog

DialogSelect.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- fix ondown and onup of lists
- add new navigation indicator

DialogSubtitles.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- fix ondown, onup and onleft of lists
- add new navigation indicator

DialogVideoInfo.xml:
- replace colors by new color variables
- add director button
- add file path and name to refresh button
- fix ondown, onup and onleft of lists
- add scrollbar to actor list
- add new navigation indicator
- add new ratings toggle for IMDb, Metacritic, Rotten Tomatoes and TVDb

EventLog.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- add submenu indicator include

FileBrowser.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- fix ondown and onup of lists
- add new navigation indicator

FileManager.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- fix ondown and onup of lists

Font.xml:
- change systeminfo font from LiberationMono-Regular.ttf to SourceSansPro-Regular.tff (default font)
- add new font 29 for media tags

GameOSD.xml:
- replace colors by new color variables

Home.xml:
- add new onloads
- replace colors by new color variables
- add onload to show welcome screen when Home screen first shows up
- add onloads for new OSD settings

Include_DialogSettings.xml:
- replace colors by new color variables
- fix ondown, onup, onleft and onright of lists
- add new navigation indicator include

Include_Home_OSMC.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- change submenu animations for new submenu indicator behaviour
- add submenu indicator
- add scrolling to focused main menu list labels
- remove reloading indicator for widgets

Includes.xml:
- add player icon to now playing dialog
- rework Overlay include
- remove Custom color Overlay include
- replace colors by new color variables
- add new include files
- fix position and size of duration icon
- prevent size from being shown when file is 0B on all platforms
- add new SubmenuIndicator include
- fix duration icon of media flags
- add new dialogButtonIndicator include
- change font of media tags to prevent overlap in certain views

Includes_Widgets.xml:
- replace colors by new color variables
- always show widget headings (when focused and non-focused)
- add reload indicator to widget headings
- change widget heading animations to match widget animations

LoginScreen.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- fix onright of the list
- add submenu indicator
- add onloads for new OSD settings

MusicOSD.xml:
- replace colors by new color variables

MusicVisualisation.xml:
- replace colors by new color variables
- add album year
- add bigger cover art

MyGames.xml:
- replace colors by new color variables
- add submenu indicator include

MyMusicNav.xml:
- replace colors by new color variables
- add wide list to music
- add new scrollbar for new view
- add submenu indicator include
- add clean library option to sub-menu

MyMusicPlaylistEditor.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- fix onup and ondown of button list

MyPics.xml:
- replace colors by new color variables
- add submenu indicator include

MyPlaylist.xml:
- replace colors by new color variables
- add submenu indicator include

MyPrograms.xml:
- replace colors by new color variables
- add submenu indicator include

MyPVRChannels.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- add adjustable plot font
- add submenu indicator include

MyPVRGuide.xml:
- replace colors by new color variables
- remove scrollbar
- add highlighting
- add adjustable plot font
- add submenu indicator

MyPVRRecordings.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- add adjustable plot font
- add submenu indicator include

MyPVRSearch.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- add adjustable plot font
- add submenu indicator include

MyPVRTimers.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- add submenu indicator include

MyVideoNav.xml:
- replace colors by new color variables
- add new wide list low view to video
- add new wall low view to video
- add new wall small view to video
- add new scrollbars for new views
- add submenu indicator include
- add new list info view to video
- add new wall info view to video
- add clean library option to sub-menu

MyWeather.xml:
- replace colors by new color variables
- add submenu indicator include

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
- fix ondown, onup, onright and onleft of lists
- add new navigation indicator include

script.skinshortcuts-static-xml:
- hack game widget to show proper widget title
- replace colors by new color variables
- change standard TV shows widget to "Random TV shows"
- adjust game widget heading to match new widget headings
- remove special non-focused heading
- add location to weather widget heading
- fix conditional visibility for Rip CD feature (only show for audio CDs)

script-skinshortcuts.xml:
- replace colors by new color variables
- fix ondown, onup, onright and onleft of lists
- add new navigation indicator include
- add option to change widget labels

Settings.xml:
- replace colors by new color variables

SettingsCategory.xml:
- replace colors by new color variables
- replace focus variable for button highlighting
- add onload to show welcome screen after activating the skin from settings
- add submenu indicator

SettingsProfile.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- replace focus variable for button highlighting
- add submenu indicator

SettingsScreenCalibration.xml:
- replace colors by new color variables

SettingsSystemInfo.xml:
- replace colors by new color variables
- replace focus variable for button highlighting
- add submenu indicator

SkinSettings.xml:
- add new onloads
- replace colors by new color variables
- add new color category
- add page indicators to new color category
- rework default background image option
- remove old background and overlay color options
- add skin settings backup and restore option
- fix onup and ondown for addons submenu
- add new adjust music OSD album art size option to advanced skin settings
- un-comment skinhelper widgets button
- add page indicators to longer add-ons category
- rework add-ons category
- comment out next-up notification add-on (it's broken)
- add onloads for new OSD settings
- add new OSD settings section

SmartPlaylistEditor.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- replace focus variable for button highlighting
- fix onup and ondown of the list

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
- fix StatusOverlay and StatusOverlayWide variables for resumable items
- fix Duration variable formatting used for media flags
- un-comment addon-skinhelperwidgets variable
- update VideoPlayerPlot, VideoPlayerTitle and VideoPlayerNext variables for new OSD settings

VideoFullScreen.xml:
- replace colors by new color variables
- add PVR timeshift status dialog
- fix current position/time remaining for PVR playback
- add PVR progress bar
- fix current time/end time for PVR playback
- add onloads for OSD settings alarm
- adjust conditional visibility of progress bar and info dialog for new OSD settings
- add elements formerly present in fullscreen info and seekbar dialog

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
- remove onright submenu

Viewtype51.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- add adjustable plot font
- remove onright submenu

Viewtype52.xml:
- replace colors by new color variables
- add albums and artists as allowed container content to conditional visibility
- add required image thumbs for artists and albums
- remove onup submenu

Viewtype53.xml:
- replace colors by new color variables
- remove onright submenu

Viewtype54.xml:
- replace colors by new color variables
- fix highlighting in focusedlayout of grouplists
- remove onright submenu

Viewtype55.xml:
- replace colors by new color variables
- remove onright submenu

Viewtype56.xml -> Viewtype521.xml:
- new wide list low view
- remove onup submenu
- rename to Viewtype521

Viewtype57.xml -> Viewtype533.xml:
- new wall low view
- remove onright submenu
- rename to Viewtype533

Viewtype58.xml -> Viewtype532.xml:
- new wall small view
- remove onright submenu
- rename to Viewtype532

Viewtype511.xml:
- new list info view

Viewtype531.xml:
- new wall info view

last_watched_TV_shows.xsp:
- add new "Last watched TV shows" smart playlist for widgets

random_artists.xsp:
- add new "Random artists" smart playlist for widgets

random_TV_shows.xsp:
- add new "Random TV shows" smart playlist for new standard TV shows widget

recent_watched_TV_shows.xsp:
- add new "Recent TV shows" smart playlist for widgets

strings.po:
- add new localizes for reworked skin settings (31052, 31097, 31107, 31108, 31109, 31110, 31111)
- add new localizes for new views (31112, 31113, 31114)
- add new localize for new music OSD album art size option (31115)
- change localizes for views (31112, 31113, 31114)
- add new localizes for new views (31116, 31117)
- add new localize for new standard TV shows widget (31118)
- add new localize for adjusted skin settings add-ons list (31119)
- add new localizes for new ratings toggle (31120, 31121, 31122)
- add new localizes for new OSD settings (31123, 31124, 31125, 31126, 31127, 31128, 31129, 31130, 31131, 31132)

Textures.xbt:
- update file with new resolution select icon included
- update file with new background gradient overlays and removed old background PNGs
- update file with new submenu indicator icons
- update file with new navigation indicator icons

341.DATA.xml:
- fix conditional visibility for Rip CD feature (only show for audio CDs)

overrides.xml:
- simplify game home menu entry and game widget
- change standard TV shows widget to "Random TV shows"
- remove unused Skin helper widgets node

template.xml:
- replace colors by new color variables
- remove special non-focused heading
- add location to weather widget heading

addon.xml:
- bump version to 18.0.0