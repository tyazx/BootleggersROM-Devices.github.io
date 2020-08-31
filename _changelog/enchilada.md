---
codename:enchilada
---
=====================
    25/11/2018
=====================

Initial build

=====================
    27/11/2018
=====================

Gapps included
OOS Camera is updated
Google Camera intergrated
ARCore and ARStickers out of the box
Fix AOD disappearing after some time
Updated Bootleggers Source

=====================
    06/12/2018
=====================

Going Official
Dec Update added
Updated gcam
Updated OOS camera from OB8
Added new gestures finally. (enjoy them)
Smartbar fling added
Battery stats are fixed

=====================
    18/12/2018
=====================

Pin HOME application in memory
Updated Gallery

=====================
    28/12/2018
=====================

Changed kernel from franco kernel to Illusion Kernel
Fixed Double Tap to wake
Fixed camera freezing sometimes
Removed ARStickers. This is because i feel playground is more superior. You just need to download [URL="https://f.celsoazevedo.com/file/gcamera/ar/Playground_All_Pack_V1.8build-2.1.181127086.apk"]PlayGround Apk from here[/URL] or [URL="https://f.celsoazevedo.com/file/gcamera/ar/ARStickers_All_Pack_V1.5build-1.3.180720036.apk"]ARStickers from here[/URL]
Gcam Updated
Rom Side changes [URL="https://del.dog/lasogaqipe.coffeescript"]here[/URL]

=====================
    09/01/2019
=====================

Merged January Update
Added toggle for volume slider to the left(You may need to reboot in order for that to work)
Add vibration sliders for incoming calls and notifications
Updated gcam thanks to Arnova as usual

=====================
    16/01/2019
=====================

Add advanced settings for Ambient Display
Some doze fixes
Fix HighBrightnessMode being enabled on boot
Fix Display Mode constantly reverting to Night Mode (DCI-P3 ftw!)
Add toggles for sim slot (can't disable all sim cards for obvious reasons)
Remove + from kernel version
Fix USB mode not being switchable
Blacklist /vendor overlays
Some SEPolicy fixes
Add CNE/DPM/Qti blobs to fix some Sim issues
Rebase device sources to remove unnecessary jank (size of the zip is finally under 1 gb)

=====================
    28/01/2019
=====================

Clean Flash is mandatory
Added clock gradients to lockscreen(those are absolutely gorgeous)
Fix Google Pay(thanks to anriudh and his entire tester team)
Fix idle drain(can legit say that the drain is almost none)
Wifi issue fixed
For rest of the detail changes follow [URL="https://forum.xda-developers.com/showpost.php?p=78772352&postcount=431"]here[/URL] and Bootleggers github

=====================
    07/02/2019
=====================
Clean Flash is mandatory to avoid problems
February Security Patch updated
OTA implemented
Gapps removed
OmniStyle headers included
Upstream kernel to 4.9.154
Add a Magisk executable script to utilise the complete capability of the kernel
Fix timings of the non-Magisk ramdisk for efficient apply of values
Allow sensors to access /dev/sensors
Some netmgrd fixes
Some SEPolicy fixes
For the rest check their github

=====================
    15/02/2019
=====================
Clean Flash is mandatory
Added extended audio panels
Show Bluetooth Battery Percentage when available
Smart Pixels as requested
Fix no Default ringtone for SIM 2
Some of the options are removed from one place to the other to get an organised view

=====================
    28/02/2019
=====================                       

Launcher3 and updates fixes           
Added a preview image to Panel Modes           
Kernel upstreamed to 160             
Added gboard go           
Some build fixes for maintainers       

=====================
    28/02/2019
=====================                             
March security Update            
Statusbar clock switched up to DU + LOS implementation (Credits to AquariOS team)                          
Fixed small derp on statusbar logo that shows the icon as intended and not very close to clock                              
Fixed App sugestion padding bug on Launcher3                        
Kernel upstreamed to .162 and built with clang 8.0.9                                                  
Update gcam(thanks to arnova)

=====================                                                      
    29/03/2019                                           
=====================                                               
* Fixed derps on powermenu toggle and secure power menu                                   
* ROM rebase to fix statusbar clock, now it should be work correctly, and even behave nicely on notch devices!                           
* Statusbar Headers                                               
* Lockscreen clocks                                                       
* Launcher3 rebased and completely up-to-date                                                       
* Switch volume panel position + Extended                                  
* Smart Pixels                                             
* Grid recents are back                                         
* Recents clear all + membar                                                      
* Support for elmyra sensor (Active edge for the squeezy bois)                                                    
* LS cover art filters, like grayscale and blur (might be buggy)                                           
* Kill all on notifs guts                                             
* Ambient ticker with new UI (based on Q beta)                                            
* Minimal stuff, like FP vibration authentication, disable qs slide on secured phones, tiles like sync and ambient display               
* Added our OTA app                                                 
* Switched to gboard go and phonograph                                                   
* Removed woodman                                                   
* Slim Recents                                             
* Added changelog section                                                   
* Themes: Themed more apps like OTA, Dialer, Contacts, File manager and phonograph                                     
* WPS Support                                                        
* OP gestures                                                              
* Smart and quick pulldown                                                                     
* Some more optimization to Ambient Ticker and many other features                                                              
* Added john notwoodman, who isn't woodman                                                                      
* Kernel Upstreamed to  .166                            
* Clang used is 9.0.2                

=====================                       
    04/04/2019                                                            
=====================                                                                            
* Fixed a system hang caused by disabling edge gestures (credits to jenslody)                                                
* Themed All apps search bar on Launcher3                                     
* Updated Links on Dumpster > About and also, removed G+ because that social network went to the same place our childhood puppy went, hope both come back soon :(                                                  
* Fixed a derp with the ShishuOTA overlay on Shishu Nights                                                               
* Added missing permissions for Pixel/Devices without debug props for permissions.                                           
* Added some missing headers on OmniStyle                                                             
* Fixed glitch on LS Filters for players like Phonograph, Black Player, etc, and also added 2 new effects, accent tinted cover art and grayscaled + blurred cover art                                                              
* Remove lawnchair from default applications since it is causing frame drops
* April Security patch merged


=====================                                             
    10/05/2019                                                                                               
=====================                                
* May Security Patch merged                               
* Kernel Upstreamed to .174           
* Updated clang                                         
* Aggressive Battery Saver options added(Thanks to carbon team)                               
* System uptime added                                
* Three finger screenshot now working better thanks to PE team.                                                
* Nfc improvements                           


=====================                                             
    01/06/2019                                                                                               
=====================                                
* Supports Wifi Cast              
* Kernel upstreamed
* Change alarms only mode to silent ringer        


=====================                                             
    11/06/2019                                                                                               
=====================                    
* Android Auto presumably fixed
* Added translations
* Fixed emergency icon tinting, credits to PE
* Rebased telephony repos
* Lockscreen date styles
* Shishu Themes now have LIT instead of LTE
* Added Q clock with extra changes for date and owner
* Aggresive Battery
* Custom fingerprint icons for OP devices
* Fixed Markup building for all devices
* Added Q seekbar with a small ui change
* Added improvements for 3 finger screenshot
* Re-introduced Woodman due to devices bootlooping
* One Hand UI
* Pixel Navbar animation
* Some extra undocumented kanging for legal reasons
* Added some new QS styles
* Fixes and improvements
* Launcher3 now has the window to icon animations, and also, fixed dark google feed
* Revert: Revert: [DO NOT MERGE] Partial Revert of john woodman





=====================                                             
    07/07/2019                                                                                               
=====================      
* July Security patch.           
* Some minor changes too busy to type       

=====================                                                    
    06/09/2019                                                                                                   
=====================                         
* Gaming Mode v2 -Now with roblox support-
* Fixes for QS detailed view
* Advanced location enabled
* Added support for Pixel stand
* Updated some boost framework stuff
* Adding cutout force full screen
* Shishu Launcher Free with a premium upgrade added
* Added LiveDisplay
* Force powersave on system apps
* New intro for new devices
* Moving net indicator to expanded statusbar header
* Fixes for Q clock strings
* Long screenshot
* Internal Audio recording
* New launcher quickspace stuff: Adding now playing -even though it's not fully compatible-, Personality (taken from lawnchair) and a new UI, more minimalistic
* Fixed the inverted navbar layout
* People actually fell off thinking that Shishu Launcher Premium was a thing, so we reverted that joke on our changelog
* Switched to Lineage Fingerprint on Display code
* Added support for sliders for OP devices
* Added some goofy stuff: like The Drill and Developer mode insulter
* Updated our APNs
* Fixed dialer dark numbers on numpad
* Misc fixes
* Removed Roblox as system app



=====================     
     10/09/2019                                                                                                   
=====================  
* September security patch                  
* Network icons fixed.                 
* More bug fixes and optimisations




=====================                         
     15/02/2020                     
=====================                         
* Initial Build                       
* Feb Security Patch



=====================                         
     24/04/2020                     
=====================       

* Source rebase from march security patch
* April Update
* Fixed/updated some overlays regarding system colors support, not updated on current themes as they had issues.
* Some gesture navbar changes, like hiding the pill and haptic feedback
* Notification light support
* Lockscreen charging extra info
* VoLTE icon
* Customization for clock and battery icons
* Updated network traffic
* Smart charging
* Toggle data icon and roaming
* Added new Partial Screenshot UI from LOS, and long screenshot support
* Forgot to take the trash out, brb
* Brightness slider customization
* Added the classic sammy clocks, with custom font support
* New spicy clocks from our kitchen: Divided Lines, SFUNY, Oroño and 2 based on MNML Lock Clock Mods (credits to AmalD)
* Switched from LOS recorder to AOSP internal one, with the new R based dialog, credits to DU
* QS Blur
* Pocket mode
* Switched the LS blur down to 7 instead of 25
* Added all the launcher funnies: From our intro to the custom messages, to the new UI made by us, to a new Now Playing that has more compatibility than the previous iteration
* More support of custom system fonts, it can be better.
* Switched from camera roll to a purified version of QuickPic made by WSTxda from WSTprojects
* Added new icon pack (enabled by default on shishufied builds) made by simrat39
* Added LOS protected apps (only works on Launcher3, sorry lawnchair folks)
* And maybe more

Device Side Changes -
* Lockscreen shows Dash Charging when you use dash charger
* Alert Slider pop-ups
* OOS camera functional(60fps is rarted)
* Blobs updated to OB6
* Volume slider added to the left
* Gcam added
* Many more changes which i forgot


=====================                         
     28/04/2020                     
=====================       


* Styles got fixed
* Updated blobs to 10.3.3
* Added QS tiles - NFC and Sound Search

=====================                         
     09/05/2020                     
=====================

* May Security Patch
* Twrp inbuilt
* Added more QS Tiles


=====================                         
     11/06/2020                     
=====================
* June Security Patch
* Add launch music player on headset connect(wired headphones only)
* More QS tiles
* Show seconds in clock

=====================                         
     11/06/2020                     
=====================
* July Security Patch
* Track new Shishu Walls
* Add new bt implementation
* Replace Calender with Etar

=====================
     31/08/2020
=====================              
- Fixed some bugs, some related to themes, some in other parts (like Lockscreen cover art)
- Added LiveDisplay support
- Updated system recording to remove any restriction
- Clipboard access toast
- Added more theming elements 
  (NOTE: in that theme elements, we also brought up Shishu Themes, excepting 2. Sorry but cosmos and protostar were too cringe)
- Added POSP volume panels (Compact, Oreo and that)
- Added pulse
- Removed any reference to based department because we were posting cringe
- Live Volume Steps
- Notif Counters
- Custom carrier stuff
- Logos in statusbar
- New VoLTE icon, made it smaller because of notch limitations
- QS Tile Styles are back
- App network restrictions 
- Toggle for qs arrows
- Header offset and QS Header styles 
- New ringtone and alarm sounds made by @ElDainosor
