**Changes to the OSMC Skin**

---

**_v20.2.0 - December 2023_**

_New_
- add new setting to adjust select action of album, TV show and movie set main menu widgets
- add consistent reminder icons for v20 PVR reminder feature
- add genre colours to TV/radio guide

_Improved_
- improve live TV and radio related localizes
- improve pre-playback behaviour of now playing information section in the top right corner of each window/dialog
- improve consistency between PVR windows and dialogs (feature parity as well as cosmetic appearance)
- improve media flags behaviour during window transitions and when encountering edge cases
- improve progress feedback of confirm dialog as well as the extended progress notification

_Fixed_
- fix focus cover animation in wide views
- fix media flags transition glitch
- fix radio button control text width
- fix behaviour when the correct view type or content type is not yet ready (especially related to addons loading new pages)

---

**_v20.1.0 - August 2023_**

_New_
- add composer info to fullscreen music playback window and music info dialog

_Improved_
- rework seek indicator and button behaviour

_Fixed_
- fix watched indicator background in wide and wall views
- fix episodes image to properly react to hide thumbs for unwatched episode setting

---

**_v20.0.0 - June 2023_**

_New_
- Support Nexus skin engine features
- remove Skin Helper Service ColorPicker support
- add new video OSD audio and subtitle selection
- add missing PVR guide controls dialog
- use new OSMC specific video width and height info for media flags
- add new default widgets to movies, tv shows and music home screen items

_Improved_
- improve inital info dialog button focus behaviour

_Fixed_
- fix view type button supression behaviour in video media window while video addon force view setting is enabled

---

**_v19.1.4 - May 2023_**

_Improved_
- improve background overlay rendering
- improve media flags spacing and positioning
- improve rendering of all progress bar, scroll bar and slider controls
- improve non-focus fanart behaviour

_Fixed_
- fix seek slider mouse control

---

**_v19.1.3 - September 2022_**

_Improved_
- improve window draw performance
- rework home screen widget animation and heading/details behaviour

_Fixed_
- use proper localize for Player settings entry
- fix default (non-skinshortcuts) home menu widget headings

---

**_v19.1.2 - March 2022_**

_New_
- reset textboxes to top scrolling position during dialog or window switches

_Improved_
- improve inital window/dialog focus fix (only apply where needed)

_Fixed_
- always show OSD playlist button when expected

---

**_v19.1.1 - December 2021_**

_New_
- add new video/music OSD seek slider button functionality (also adds frame advance feature)
- add settings level button and settings description to addon settings dialog

_Improved_
- improve behaviour of OSD bookmarks dialog while other OSD dialogs are open (similar to previous OSD animation improvements)
- streamline addon settings and skinshortcuts customization dialogs

_Fixed_
- fix initial focus in all windows and dialogs

---

**_v19.1.0 - August 2021_**

_New_
- add ENABLE option for new skinshortcuts version
- add playback mode (shuffle and repeat) buttons to video OSD
- add comment tag line to music visualisation
- add new menu/OSD opacity/colour settings
- add new plain colour background overlay style option matching the new skin design

_Improved_
- improve background overlay colour management of new skin design
- streamline secondary information and widget detail labels
- improve weather widget
- add warning to add-ons currently not available from Kodi repo
- allow jumping from top to bottom of video playback settings dialog
- adjust list views to change depending on secondary label status
- improve settings window with new description and better list behaviour
- update translations
- handle movie set/collection indication more seamlessly
- improve dialog animations
- improve OSD animations
- change focus of info dialog button lists to extended info button

_Fixed_
- fix skinshortcuts management dialog
- add missing views to programs section for addons that set content type
- fix dialog select icons for movies and TV shows
- fix movie set information in media library views
- fix seek indicator

---

**_v19.0.0 - August 2021_**

_New_
- add new v19 features (music library, movie sets, PVR additions and chapter/EDL markers in video OSD)
- add channel sort by and sort order toggles to PVR guide side menu
- add artist, album and radio now/next/RDS information to fullscreen music/radio playback window
- add new info button to video and music OSD
- add trackt.tv ratings information to video info dialog
- add first WebLate translations
- new skin design

_Improved_
- rework look of default fullscreen music playback screen to match general skin look
- refine video fullscreen OSD and info dialog behaviour
- improve behaviour of weather widget when no weather information is available
- improve widget headings and general secondary label information
- improve localize consistency
- add missing custom colour settings
- improve skin setting select process for settings with a lot of options to choose from
- use translatable labels for skin setting options
- improve media flags positioning and edge case handling
- move My OSMC link from home menu to settings window

_Fixed_
- add missing "play recorded programme" button to PVR info dialog
- fix cut-off text of plot/description text boxes

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
- rework skin structure for Transifex localization
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
- add new multi-image (folder) background option
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
- new colour options (colour sets, background gradients, adjustable opacity)
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
- highlighting colour now adjusts according to text color
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
- improve highlight colour of selected text
- change appearance of all progress icons to round shape
- add no dimming of cover art
- dim watched and collection indicator depending on cover dimming setting
- update watched overlay icon to match appearance of new movie collection indicator
- add current control ID to debug overlay
- change overlay colour setting to match appearance of background colour setting

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
- fix custom background colour option
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

**Changelog v20.1.1**

_rename default live TV home menu items to use new heading localize ID_

strings.po:
- add localizes for new adjust select action of album, TV show and movie set main menu widgets settings (31438, 31439, 31440, 31441, 31442, 31443)
- remove deprecated live TV localize and replace it with new favourite content label (31015)
- remove deprecated search result and timer localizes (31293, 31433, 31434)
- add new localizes for TV/radio guide genre colour setting (31293, 31433)

textures.xbt:
- update textures file with new TV/radio guide genre colour assets

mainmenu.DATA.xml:
- replace live TV home menu item localize to use the new localize ID

overrides.xml:
- rework TV and radio nodes for home menu item and widgets sections using the new localize ID for the TV section

template.xml:
- add new widget onclick controls
- add new recording, timer and reminder icons to the widget template

Coordinates_Custom_DialogMasking.xml:
- rework coordinates includes to add and adjust textwidth tags for radio button controls

Coordinates_DialogAddonSettings.xml:
- rework coordinates includes to add and adjust textwidth tags for radio button controls

Coordinates_DialogExtendedProgressBar.xml:
- add coordinates includes for new progress bar busy spinner icon

Coordinates_DialogKeyboard.xml:
- rework coordinates includes to add and adjust textwidth tags for radio button controls

Coordinates_DialogPVRChannelGuide.xml:
- add new reminder icons and rework recording and timer icons for consistency

Coordinates_DialogPVRChannelManager.xml:
- rework coordinates includes to add and adjust textwidth tags for radio button controls

Coordinates_DialogPVRChannelsOSD.xml:
- add missing recording and timer and new reminder icons

Coordinates_DialogPVRGroupManager.xml:
- add missing channel icons to lists

Coordinates_DialogPVRGuideSearch.xml:
- rework coordinates includes to add and adjust textwidth tags for radio button controls

Coordinates_DialogSettings.xml:
- rework coordinates includes to add and adjust textwidth tags for radio button controls

Coordinates_Includes_SubMenu.xml:
- rework coordinates includes to add and adjust textwidth tags for radio button controls

Coordinates_Includes_Time_NowPlaying.xml:
- add coordinates includes for new dialog confirm busy spinner icon

Coordinates_MyPVRChannels.xml:
- rework coordinates includes for more consistent window look
- add missing recording and timer and new reminder icons

Coordinates_MyPVRGuide.xml:
- fix colours of timer and reminder icons
- adjust position of recording, timer and reminder images to prevent overlap with added highlighting textures
- adjust TV/radio guide background textures for new TV/radio guide genre colours

Coordinates_MyPVRRecordings.xml:
- rework coordinates includes for more consistent window look
- add missing recording and timer and new reminder icons

Coordinates_MyPVRSearch.xml:
- rework coordinates includes for more consistent window look
- add missing recording and timer and new reminder icons

Coordinates_MyPVRTimers.xml:
- rework coordinates includes for more consistent window look
- add missing recording and timer and new reminder icons

Coordinates_script-skinshortcuts.xml:
- add new coordinates includes to add textwidth tags for radio button control

Coordinates_SettingsCategory.xml:
- rework coordinates includes to add and adjust textwidth tags for radio button controls

Coordinates_SettingsProfiles.xml:
- rework coordinates includes to add and adjust textwidth tags for radio button controls

Coordinates_SkinSettings.xml:
- rework coordinates includes to add and adjust textwidth tags for radio button controls

Coordinates_SmartPlaylistEditor.xml:
- rework coordinates includes to add and adjust textwidth tags for radio button controls

Coordinates_Viewtype52.xml:
- fix focus cover animation

Coordinates_Viewtype521.xml:
- fix focus cover animation

Coordinates_Viewtype522.xml:
- fix focus cover animation

Coordinates_Viewtype523.xml:
- fix focus cover animation

Coordinates_Viewtype524.xml:
- fix focus cover animation

Coordinates_Viewtype525.xml:
- fix focus cover animation

Defaults.xml:
- adjust textwidth tag of default radio button control

DialogAddonInfo.xml:
- adjust textwidth tag of radio button control

DialogConfirm.xml:
- adjust time include for new progress busy spinner icon

DialogExtendedProgressBar.xml:
- add new busy spinner icon

DialogFavourites.xml:
- rework item count visibility condition and animation

DialogKeybard.xml:
- replace coordinates includes to add and adjust textwidth tags for radio button controls

DialogPVRChannelManager.xml:
- fix defaultcontrol
- replace coordinates includes of edit, button, spincontrolex and radio button controls

DialogPVRGroupManager.xml:
- fix defaultcontrol
- add textwidth tag to radio button control

DialogPVRGuideSearch.xml:
- replace coordinates includes to add and adjust textwidth tags for radio button controls

FileBrowser.xml:
- add textwidth tag to radio button control

FileManager.xml:
- rework item count visibility condition and animation

Includes.xml:
- add new onload conditions for new adjust select action of album, TV show and movie set main menu widgets settings

Includes_DialogSettings.xml:
- replace coordinates include to add and adjust textwidth tags for radio button control

Includes_MediaFlags.xml:
- add fade animation during on next and on previous transitions to hide media flags glitch
- adjust media flags animations for more consitent behaviour
- rework duration only label to incorporate MyPlaylist window more seamlessly
- rework item count visibility condition and animation

Includes_SubMenu.xml:
- adjust addon browser submenu onleft, onright and onback tags for now utilized view types 50 and 51
- replace PVR & live TV settings sub menu item localize to use the new localize ID

Includes_Time_NowPlaying.xml:
- adjust now playing labels conditional visibility for better pre-playback information (before streams or network resources are available)
- adjust time include for new dialog confirm busy spinner icon

Includes_Windows_Dialogs.xml:
- add new background transition fallback when media window view type controls are not yet visible

MyPrograms.xml:
- adjust scrollbar visibility condition to remove never used control

MyPVRChannels.xml:
- rework window for more consistent look

MyPVRGuide.xml:
- rework item count visibility condition and animation
- add new colour diffuse variable to guide grid progress timeline

MyPVRRecordings.xml:
- rework window for more consistent look

MyPVRSearch.xml:
- rework scrollbar position for more consistent look

MyPVRTimers.xml:
- rework scrollbar position for more consistent look

script-skinshortcuts-static.xml:
- add new widget onclick controls
- add new recording, timer and reminder icons to the widget template

script-skinshortcuts.xml:
- replace coordinates includes to add and adjust textwidth tags for radio button control

Settings.xml:
- replace PVR & live TV settings section localize to use the new localize ID

SettingsCategory.xml:
- replace coordinates includes to add and adjust textwidth tags for radio button controls

SettingsProfiles.xml:
- replace coordinates includes to add and adjust textwidth tags for radio button control

SkinSettings.xml:
- add new adjust select action of album, TV show and movie set main menu widgets settings
- replace coordinates includes to add and adjust textwidth tags for radio button controls
- add setting for new TV/radio guide colours

Variables.xml:
- add new value condition to HeadingLabelSecondary variable for new PVR & live TV settings section localize ID
- rework PlayerIcon variable for better pre-playback player icon
- add new epggridunfocusdim variable for unfocus dimming of TV/radio guide grid progress timeline

Variables_Settings.xml:
- add new variable values to SkinSettingsExplanation for new adjust select action of album, TV show and movie set main menu widgets settings
- add new variable value for TV/radio guide colour setting explanation text

Variables_Skinshortcuts.xml:
- add new WidgetOnClickAlbum, WidgetOnClickTVShow and WidgetOnClickMovieSet variables for new widget onclick controls

Viewtype50.xml:
- rework view type for better content type related icons and instances where the content type is returned empty

Addon.xml:
- bump version to 20.2.0
- update changelog

Changelog.md:
- update changelog
