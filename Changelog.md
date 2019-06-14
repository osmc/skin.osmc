**Changes**

_New_
- add new video player OSD settings (show OSD after beginning of playback and before end of playback)
- add new second video info dialog screen (with extended rating, audio and subtitle information and bigger plot text box)
- add new wall info view (based on wall view)
- add new adjust representation of video duration setting
- add new multi image (folder) background option
- add new individual background option for home menu entries

_Improved_
- add audio information to video info dialog
- use font type for bold, light and italic instead of label formatting (where possible)

_Fixed_
- only offer rip CD feature when an audio CD is present

**Changelog v18.0.1**

Addon.Browser.xml:
- replace label formatting with light font
- replace label formatting with bold font
- move skin-related onloads to include
- clean-up window header

DialogAddonInfo.xml:
- fix syntax
- replace label formatting with light font

DialogFavourites.xml:
- replace label formatting with light font
- replace old bold font

DialogFullScreenInfo.xml:
- remove info dialog

DialogMusicInfo.xml:
- replace label formatting with light font

DialogPlayerProcessInfo.xml:
- replace label formatting with light font

DialogPVRChannelGuide.xml:
- replace label formatting with light font
- replace label formatting with bold font

DialogPVRInfo.xml:
- replace label formatting with light font
- replace label formatting with bold font

DialogSeekBar.xml:
- remove PVR channel number input dialog

DialogSelect.xml:
- replace label formatting with light font
- replace label formatting with bold font

DialogVideoInfo.xml:
- add onload and onunload for new second info screen
- fix conditional visibility of poster/actor images, info list and cast list for use with new second info screen
- fix positioning of actor image
- add audio information
- adjust plot text box and make it show plot outline (shorter and no spoilers)
- fix positioning of cast list
- fix positioning of cast list scrollbar
- add second info screen (with extended rating, audio and subtitle information and bigger plot text box)
- add conditional visiblity to only show play and return button in second info screen
- add extended info button
- replace label formatting with light font

EventLog.xml:
- replace label formatting with light font
- replace label formatting with bold font

FileBrowser.xml:
- replace label formatting with light font
- replace label formatting with bold font

FileManager.xml:
- replace label formatting with light font
- replace label formatting with bold font

Font.xml:
- add bold, light and italic version to each font size

Home.xml:
- move skin-related onloads to include
- clean-up window header

Includes.xml:
- add new include file for new view
- replace label formatting with light font
- change background image include for new multi image (folder) background option
- add CustomBackgroundFolderDuration include for new multi image (folder) background option
- add new Onloads include for skin-related onloads
- change fanart image control to multi image control

Includes_Widgets.xml:
- replace label formatting with bold font

Include_Home_OSMC.xml:
- replace label formatting with light font
- replace label formatting with bold font

LoginScreen.xml:
- replace label formatting with light font
- replace label formatting with bold font
- move skin-related onloads to include
- clean-up window header

MusicVisualisation.xml:
- replace label formatting with light font
- replace label formatting with bold font

MyPVRChannels.xml:
- fix alignment of plot textbox
- replace label formatting with light font
- replace label formatting with bold font

MyPVRGuide.xml:
- fix alignment of plot textbox
- replace label formatting with light font
- replace label formatting with bold font

MyPVRRecordings.xml:
- fix alignment of plot textbox
- replace label formatting with light font
- replace label formatting with bold font

MyPVRSearch.xml:
- replace label formatting with light font
- replace label formatting with bold font
 
MyPVRTimers.xml:
- replace label formatting with light font
- replace label formatting with bold font

MyVideoNav.xml:
- add new view 534 and rename 531, 532 and 533
- add new scrollbar for new wall info view (old wall info is now wall small info)

script-nextup-notification-NextUpInfo.xml:
- replace label formatting with light font

script-nextup-notification-StillWatchingInfo.xml:
- replace label formatting with light font

script.skinshortcuts.xml:
- add edit background option to home menu customization dialog
- add edit background duration option to home menu customization dialog

script.skinshortcuts-static-xml:
- fix conditional visibility for Rip CD feature (only show for audio CDs)

SettingsCategory.xml:
- move skin-related onloads to include
- clean-up window header

SkinSettings.xml:
- add new adjust representation of video duration setting
- replace label formatting with italic font
- move skin-related onloads to include
- clean-up window header
- change IDs of skin settings categories
- change background settings for new multi image (folder) background option
- add skin helper backgrounds script as requirement for home menu customization
- add skin helper backgrounds script as recommended addon

Variables.xml:
- update VideoPlayerPlot, VideoPlayerTitle and VideoPlayerNext variables for new OSD settings
- add new PlotInfoDialog variable (preferring plot outline over plot for video info dialog)
- add new AudioChannels.1-.4 variables for new second info dialog screen
- add new AudioCodec.1-.4 variables for new second info dialog screen
- adjust Duration variable for new video duration setting
- change OSMCBackgroundImage variable for new multi image (folder) background option
- add new addon-skinhelperbackgrounds variable for new recommended addon

VideoFullScreen.xml:
- add onloads for OSD settings alarm
- adjust conditional visibility of progress bar and info dialog for new OSD settings
- add elements formerly present in fullscreen info and seekbar dialog
- replace label formatting with bold font
- replace label formatting with light font

Viewtype50.xml:
- replace label formatting with light font
- replace label formatting with bold font

Viewtype51.xml:
- fix alignment of plot textbox
- replace label formatting with light font
- replace label formatting with bold font

Viewtype511.xml:
- fix alignment of plot textbox
- replace label formatting with light font
- replace label formatting with bold font

Viewtype531.xml:
- fix alignment of plot textbox
- adjust size and amount of movie poster thumbs for new wall info view

Viewtype533.xml:
- make old wall info view new wall small info view

Viewtype534.xml:
- new viewtype file for old wall low view

Viewtype54.xml:
- replace label formatting with light font
- replace label formatting with bold font

SourceSansPro-Italic.ttf:
- add new font style file

SourceSansPro-Light.ttf:
- add new font style file

SourceSansPro-Regular.ttf:
- add new font file

SourceSansPro-Semibold.ttf:
- add new font style file

strings.po:
- add new localizes for extended ratings in second video info dialog screen (31120, 31121, 31122)
- add new localizes for new OSD settings (31123, 31124, 31125, 31126, 31127, 31128, 31129, 31130, 31131, 31132)
- change view localizes (31112, 31113, 31114, 31116, 31117)
- add new localize for new wall info view (31133)
- add new localize for new video duration setting (31134)
- add new localizes for new multi image (folder) background option (31135, 31136, 31137, 31138)
- add new localizes for reset path of new background option (31139)
- add new localizes for new recommended addon (31140)

341.DATA.xml:
- fix conditional visibility for Rip CD feature (only show for audio CDs)

overrides.xml:
- add background smartshortcuts and background browse overrides

template.xml:
- add value to widgetbackground variable for new background option

addon.xml:
- bump version to 18.0.1