**Changes**

_New_
- add new video player OSD settings (show OSD after beginning of playback and before end of playback)
- add new second video info dialog screen (with extended rating, audio and subtitle information and bigger plot text box)
- add new wall info view (based on wall view)
- add new adjust representation of video duration setting

_Improved_
- add audio information to video info dialog

_Fixed_
- only offer rip CD feature when an audio CD is present

**Changelog v18.0.1**

Addon.Browser.xml:
- add onloads for new OSD settings
- add onload for new video duration setting

DialogAddonInfo.xml:
- fix syntax

DialogFullScreenInfo.xml:
- remove info dialog

DialogSeekBar.xml:
- remove PVR channel number input dialog

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

Home.xml:
- add onloads for new OSD settings
- add onload for new video duration setting

Includes.xml:
- add new include file for new view

LoginScreen.xml:
- add onloads for new OSD settings
- add onload for new video duration setting

MyVideoNav.xml:
- add new view 534 and rename 531, 532 and 533
- add new scrollbar for new wall info view (old wall info is now wall small info)

script.skinshortcuts-static-xml:
- fix conditional visibility for Rip CD feature (only show for audio CDs)

SettingsCategory.xml:
- add missing onloads

SkinSettings.xml:
- add onloads for new OSD settings
- add new OSD settings section
- add onload for new video duration setting
- add new adjust representation of video duration setting

Variables.xml:
- update VideoPlayerPlot, VideoPlayerTitle and VideoPlayerNext variables for new OSD settings
- add new PlotInfoDialog variable (preferring plot outline over plot for video info dialog)
- add new AudioChannels.1-.4 variables for new second info dialog screen
- add new AudioCodec.1-.4 variables for new second info dialog screen
- adjust Duration variable for new video duration setting

VideoFullScreen.xml:
- add onloads for OSD settings alarm
- adjust conditional visibility of progress bar and info dialog for new OSD settings
- add elements formerly present in fullscreen info and seekbar dialog

Viewtype51.xml:
- fix alignment of plot textbox

Viewtype511.xml:
- fix alignment of plot textbox

Viewtype531.xml:
- fix alignment of plot textbox
- adjust size and amount of movie poster thumbs for new wall info view

Viewtype533.xml:
- make old wall info view new wall small info view

Viewtype534.xml:
- new viewtype file for old wall low view

strings.po:
- add new localizes for extended ratings in second video info dialog screen (31120, 31121, 31122)
- add new localizes for new OSD settings (31123, 31124, 31125, 31126, 31127, 31128, 31129, 31130, 31131, 31132)
- change view localizes (31112, 31113, 31114, 31116, 31117)
- add new localize for new wall info view (31133)
- add new localize for new video duration setting (31134)

341.DATA.xml:
- fix conditional visibility for Rip CD feature (only show for audio CDs)

addon.xml:
- bump version to 18.0.1