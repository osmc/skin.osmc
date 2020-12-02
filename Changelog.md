**Changes to the OSMC skin**

---

**_v18.5.0 - November 2020_**

_Improved_
- add videos and music root directory to home menu entry and submenu customization dialog
- add picture and addon browser directory to home menu entry and submenu customization dialog

---

**_v18.4.0 - October 2020_**

_New_
- add channel group switching buttons to OSD PVR channels list
- add Library Node Editor support
- new square versions of existing views for video addons and music
- add automatic masking for scope skin version
- add second dialog page to music, PVR and addon info dialog
- add setting to force a specific view for video addons
- add missing PVR seek slider

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
- add favourites to home menu entry/submenu and widget customization dialog

_Fixed_
- fix default view music and video navigation
- fix PVR channels window heading label
- fix widget icon fallback
- fix PVR OSD dialogs

---

**_v18.3.0 - May 2020_**

_New_
- add standard Kodi 'Menu' key functionality to access side menu in all windows
- add new Wide low info view
- add support for Up Next addon
- add playlist button to video OSD
- add 3D depth information to GUI elements
- add new widget layouts (square and square small)
- add new 2.33:1 scope masking option

_Improved_
- make Wide low view accessible for music views
- make disabled text colour more readable
- improve widget details and window headings
- improve debug overlay
- improve overall handling of music videos
- improve playlist window
- add missing scrollbars
- rework most dialogs for consistency
- improve widget positioning and widget icon size
- improve skinshortcuts management dialog
- improve video info dialog button behaviour
- remove unnecessary song and picture list view

_Fixed_
- fix settings button labels for 21:9 and 4:3 modes
- fix music playlist editor window
- fix side menu return button behaviour
- fix edge alignment of dialogs and windows
- fix watched/listened to status for a play count higher than 1

---

**_v18.2.0 - March 2020_**

_New_
- add new pre-defined widgets
- add setting to change whether video info dialog shows details or plot first
- add setting to set a solid colour instead of background images
- add audio and subtitle language information to media flags
- add setting to toggle media flags information shown (first)
- add new seek indicator to audio and video player
- add new scope version
- add new scrolling label
- add new never hide music information during playback setting
- add skin settings explanations
- add setting to hide item count

_Improved_
- rework home menu customization dialogs
- improve sort by and sort order toggles
- improve video info dialog (animations and buttons)
- improve alignment and positioning of item count and media flags
- show view toggle only when more than one view is available
- improve info dialogs (more information/layout with video and addon info dialogs)
- update Artist Slideshow integration (v3 update)
- improve OSD animations
- show item count with empty containers
- improve music player during radio playback
- improve visible window elements when busy dialog is active
- let live TV and radio OSD listen to Kodi OSD settings

_Fixed_
- move hide scrollbars setting to skin settings window
- hide MyOSMC home menu entry and widget on non-OSMC systems
- fix overlapping in views with big horizontal titles
- add scrollbar to music album info dialog (if details list is too long)
- fix now playing dialog for radio and live TV playback
- fix kiosk mode behaviour

---

**_v18.1.0 - November 2019_**

_New_
- add 21:9 and 4:3 modes
- add option to show lock icon for encrypted PVR channels (show encrypted channel icons by default)

_Improved_
- use OSMC busy spinner for widget loading
- add Disabled option to Adjust OSD on-time during video pause button
- rework skin structure for Transiflex localization
- improve widget icon animations
- rework dialog animations to prevent bright transition

_Fixed_
- don't show parts of weather widget during widget loading
- localize all labels

---

**_v18.0.1 - October 2019_**

_New_
- add new video player OSD settings (show OSD after beginning of playback and before end of playback)
- add new second video info dialog screen (with extended rating, audio and subtitle information and bigger plot text box)
- add new wall info view (based on wall view)
- add new adjust representation of video duration setting
- add new multi image (folder) background option
- add new individual background option for home menu entries
- add new options for music OSD to automatically show
- add user rating to music and video library
- add new side-menu player controls
- add new options to hide watched indicator in video library and listened to indicator in music library

_Improved_
- add audio information to video info dialog
- use font type for bold, light and italic instead of label formatting (where possible)
- prevent stacking of window/dialog text during background video playback
- show special watched indicator icons for videos watched more than once
- add listened to indicator for music

_Fixed_
- only offer rip CD feature when an audio CD is present

---

**_v18.0.0 - May 2019_**

_New_
- add new subtitle selection to match v18 requirements
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

---

**_v17.0.5 - June 2018_**

_New_
- add option to adjust dim factor of unfocused art 
- add option for additional text highlight
- add channel icon to PVR info dialog
- add new widget options (through skin.helper.widgets script)
- add AURO media flags (based on file naming)
- add new cover art highlighting (size change depending on focused state)
- add new movie collection indicator

_Improved_
- add more weather information to weather window
- refine music icons
- remove watched status for music items (in views and widgets)
- adjust representation of object based audio codec tags
- refine positioning and scaling of media tag icons
- adjust viewtype 55 for music and add-ons to match viewtype 53 for movies and TV shows
- improve highlight color of selected text
- change appearance of all progress icons to round shape
- add no dimming of cover art
- dim watched and collection indicator depending on cover dimming setting
- update watched overlay icon to match appearance of new movie collection indicator
- add current control ID to debug overlay
- change overlay color setting to match appearance of background color setting

_Fixed_
- fix scrollbar in music navigation
- fix item widths in various windows
- fix weather window
- fix focused items in addon list view (e.g. YouTube)
- fix PVR views to add scrolling and adapt season/episode representation
- fix widget details label for PVR items (when using skinshortcuts script)
- fix scrollbar in file browser

---

**_v17.0.4 - March 2018_**

_New_
- music track duration added to music info dialog
- 3D label shown under media flags now (after first playback and/or if named according to Kodi wiki)
- Atmos/DTS:X label shown under media flags now (if named according to Kodi wiki)
- show codec information in music “now playing” window
- show current audio/subtitle stream in info dialog during full screen video playback
- add file size label next to duration label in file view
- add adjustable font sizes/styles to plot/description texts (addon info, music info, full screen info, PVR info and video info dialog) – font sizes 27 (S), 30 (M), 33 (L) and 36 (XL) available in normal and light
- add option to show date above system time
- add option to adjust OSD on-time during video pause
- add option to hide thumbnail art of unwatched TV show episodes

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
- add cycling of controls highlight in context menu

_Fixed_
- window heading and system clock moved slightly down and reduced width of “now playing” dialog to avoid overlaps
- adjust height of plot textbox in list view to avoid overlap with new media flag representation
- use titles when available instead of item labels
- recognize TV show specials and show them correctly (no season, just episode S1)
- adjust width of scrolling titles in wall view and wide list view to avoid overlap with new media flags
- “now playing” dialog now shows album/artist tags correctly even when one of them or both are not present in the currently playing music file
- fix custom background color option
- bring back current playlist button in music OSD functionality

---

**_v17.0.3 - July 2017_**

---

**_v17.0.2 - March 2017_**

---

**_v17.0.1 - March 2017_**

---

**_v16.9.3 - January 2017_**

---

**_v16.9.3 - January 2017_**

---

**_v16.9.2 - November 2016_**

Fix crash in PVR guide window; Font updates

---

**_v16.9.1 - November 2016_**

Library image fixes and now playing information

---

**_v16.9.0 - September 2016_**

Release

---

**Changelog v18.5.0**

overrides.xml:
- add new videos and music root directory to home menu entry and submenu customization dialog
- add picture root and addon browser directory to home menu and submenu entry section

addon.xml:
- bump version to 18.5.0
