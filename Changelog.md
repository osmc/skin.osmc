v17.0.4b
--------

DialogMusicInfo.xml:
- add track duration to music info dialog

DialogMusicInfo.xml, DialogPVRInfo.xml, DialogVideoInfo.xml:
- replace duration label by a global variable for duration labels (for music, PVR and video)

DialogVideoInfo.xml:
- add "p" to resolution in video info dialog and alter representation of 4K resolutions to "2160p" (global variable used here)

Includes.xml:
- move window headings and system time slightly downwards to avoid collision/overlap with "now playing" dialog (if music/video/PVR titles are very long)
- add seconds to system time (more accurate and easier to see, whether the system crashed e.g.)
- adjust width of now playing dialog (to avoid collision with main menu items)
- adjust now playing dialog for TV shows (old format: s1e1, new format: S01E01 - capital letters and leading zeros added)
- add ": " to music now playing dialog when showing artist and album (a separator is useful here!)
- adjust time and time remaining line in now playing dialogs (copy the syntax of e.g. VideoFullScreen.xml "Current Time/End Time")
- move MediaFlags up a bit to allow two-line representation (first line for video, second for audio information)
- add a label for 3D files under MediaFlags (global variable used here)
- add a label for Atmos/DTS:X audio streams (global variable used here)
- adjust representation of audio codec IDs and channel layout (global variables used here)
- move duration label a bit to the left to clarify difference to MediaFlag labels (whitespace added in between those two as well)

MusicVisualisation.xml:
- complete redo of "Now playing" label (all lines turned into fadelabels to scroll long titles, add audio information - codec, bitrate, channel layout and sample rate -, global variables used here)
- complete redo of "Next playing" label (all lines turned into fadelabels to scroll long titles, global variables used here as labels - [CR] can't be scrolled!)

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

Viewtype51.xml:
- adjust text box height of plots shown when selecting a TV show episode in list view (to avoid collision with new MediaFlags representation)
- replace separator " / " by point separator (adapting the separator used between season and episode: "season x [separator] episode x" to the one used in list view and episode widget titles)

Viewtype52.xml, Viewtype53.xml, Viewtype55.xml:
- use variable "Label1" for titles

template.xml:
- add/adjust variable conditions needed for "SxxExx" representation in in widget titles when using script-skinshortcuts (add line to show only episode title when ListItem.Episode contains the character "s" - for series specials)

script-skinshortcuts-static.xml:
- replace fixed "(sxex) episode title" syntax with variable for "SxxExx [separator] episode title" (this file is used when script-skinshortcuts is not installed)

addon.xml:
- bump version to 17.0.4b (add beta version information)
