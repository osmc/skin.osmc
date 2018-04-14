**Changes**

_New_
- music track duration added to music info dialog
- 3D label shown under media flags now (after first playback and/or if named according to Kodi wiki, no blanks allowed)
- Atmos/DTS:X label shown under media flags now (if named according to Kodi wiki, no blanks allowed)
- show codec information in music “now playing” window
- show current audio/subtitle stream in info dialog during full screen video playback
- add file size label next to duration label in file view
- add adjustable font sizes/styles to plot/description texts (addon info, music info, full screen info, PVR info and video info dialog) – font sizes 27 (S), 30 (M), 33 (L) and 36 (XL) available in normal and light
- add option to show date above system time

_Improved_
- show resolution with “p”-suffix (global)
- show 4K resolution as 2160p (global)
- adjust playback time and finish time in “now playing” dialog to match representation in full screen video playback window
- show media flags in a two-line textbox
- translate video/audio codecs in media flags to more understandable labels
- add scrolling of long titles in “now playing” window for music
- add scrolling of long album titles/artist tags in music list view
- show more specific channel layout information (2.0, 5.1, 7.1, etc.)
- replace “Aired on” in details of TV show episodes (in list view) by translatable “First air date”
- adjust representation of season/episode titles to one syntax everywhere: S01E01
- replace "Loading…" upon widget loading at startup of mediacenter by translatable "Please wait…"

_Fixed_
- window heading and system clock moved slightly down and reduced width of “now playing” dialog to avoid overlaps
- adjust height of plot textbox in list view to avoid overlap with new media flag representation
- use titles when available instead of item labels
- recognize TV show specials and show them correctly (no season, just episode S1)
- adjust width of scrolling titles in wall view and wide list view to avoid overlap with new media flags
- “now playing” dialog now shows album/artist tags correctly even when one of them or both are not present in the currently playing music file

**Changelog v17.0.4**

DialogAddonInfo.xml:
- add different font sizes/styles (27, 30, 33 and 36 - light, normal) to addon description text

DialogFullScreenInfo.xml:
- add currently played audio/subtitle stream to video player info dialogue (global variables used here)
- add different font sizes/styles (27, 30, 33 and 36 - light, normal) to video plot text
- move now playing/next window line in info view of full screen PVR playback slightly down to avoid overlap with current audio/subtitle stream info

DialogMusicInfo.xml:
- add track duration to music info dialog
- add different font sizes/styles (27, 30, 33 and 36 - light, normal) to music plot text

DialogMusicInfo.xml, DialogPVRInfo.xml, DialogVideoInfo.xml:
- replace duration label by a global variable for duration labels (for music, PVR and video)

DialogPlayerProcessInfo.xml:
- add video and audio codec (global variables used here)

DialogPVRInfo.xml:
- add different font sizes/styles (27, 30, 33 and 36 - light, normal) to PVR plot text

DialogSubtitles.xml:
- change filename label into fadelabel to enable scrolling
- add scrolling to subtitle name label

DialogVideoInfo.xml:
- add "p" to resolution in video info dialog and alter representation of 4K resolutions to "2160p" (global variable used here)
- add different font sizes/styles (27, 30, 33 and 36 - light, normal) to video plot text

Includes.xml:
- move window headings and system time slightly downwards to avoid collision/overlap with "now playing" dialog (if music/video/PVR titles are very long)
- adjust width of now playing dialog (to avoid collision with main menu items)
- adjust now playing dialog for TV shows (old format: s1e1, new format: S01E01 - capital letters and leading zeros added)
- add ": " to music now playing dialog when showing artist and album (a separator is useful here!)
- adjust time and time remaining line in now playing dialogs (copy the syntax of e.g. VideoFullScreen.xml "Current Time/End Time")
- move MediaFlags up a bit to allow two-line representation (first line for video, second for audio information)
- add a label for 3D files under MediaFlags (global variable used here)
- add a label for Atmos/DTS:X audio streams (global variable used here)
- adjust representation of audio codec IDs and channel layout (global variables used here)
- move duration label a bit to the left to clarify difference to MediaFlag labels (whitespace added in between those two as well)
- adjust font size of item list count
- delete file size label (just show size)
- move file size label from bottom right to bottom left corner next to the duration label (under file view)
- adjust "now playing" dialog to show information of music files without artist and/or album tag correctly
- add system date label to system time include in top right corner (only visible with a skin setting)
- adjust "now playing" dialog for audio addons which only provide a playback length of 0

MusicVisualisation.xml:
- complete redo of "Now playing" label (all lines turned into fadelabels to scroll long titles, add audio information - codec, bitrate, channel layout and sample rate -, global variables used here)
- complete redo of "Next playing" label (all lines turned into fadelabels to scroll long titles, global variables used here as labels - [CR] can't be scrolled!)

MyMusicNav.xml:
- move wall scrollbar down (for view 55)

MyPrograms.xml:
- move wall scrollbar down (for view 55)

script-skinshortcuts-static.xml:
- replace fixed "(sxex) episode title" syntax with variable for "SxxExx [separator] episode title" (this file is used when script-skinshortcuts is not installed)
- replace "Loading…" by a LOCALIZE showing "Please wait…" (replacing only English line)

SkinSettings.xml:
- add new button for description/plot text font size under advanced skin settings
- add new button to toggle light font for description/plot texts under advanced skin settings
- add new button to toggle "Show date above system time" option under home skin settings

Variables.xml:
- complete redo of variable "AudioChannels" (not only stereo and surround as output, but all supported channel layouts)
- add variable "MusicPlayerChannels" (to be used in MusicVisualisation.xml)
- add variables under "Audio Codec labels" (Atmos, DTS:X, AudioCodec and MusicPlayerCodec - to be used in Includes.xml and MusicVisualisation.xml)
- add variable "Duration" (global, easy to use variable for any duration representation of files - differentiating between 00 output and 00:00:00 output)
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

template.xml:
- add/adjust variable conditions needed for "SxxExx" representation in in widget titles when using script-skinshortcuts (add line to show only episode title when ListItem.Episode contains the character "s" - for series specials)
- adjust episode widget title to always use uppercase for "Sx" format of specials
- replace "Loading…" by a LOCALIZE showing "Please wait…" (replacing only English line)

addon.xml:
- bump version to 17.0.4
