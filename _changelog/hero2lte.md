---
codename:hero2lte
---
=====================
    10/06/2019
=====================
- Updated kernel to 3.18.140
- Updated rom to June security update
- Updated prop. binaries to May security updated
- Removed unused gralloc usage bits flag
- Synced with Bootleggers source (4.2):
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
    17/05/2019
=====================
- Fixed HWC
- Updated kernel to 3.18.139
- Updated vendor security patch to match (Latest at the moment samsung decided to drop support for monthly patches on s7 so they update it every 3 months now, we dont use a lot of blobs from stock anyway so this is non issue)
- Updated system security patch to may
- Enabled quota support on /data (Make sure you are on latest twrp)
- Misc performance and stability improvements
- Synced with Bootleggers source (4.1)

=====================
    17/04/2019
=====================
- Enabled Smart Pixels
- Reflux Kernel R14:
  * Upstreamed to Linux 3.18.138
- Synced with Bootleggers source (4.1)

=====================
    06/04/2019
=====================
- Updated to April security patch
- Reflux Kernel R14:
  * Added Moro Sound Control v2.1
- Synced with Bootleggers source (4.1):
  * Fixed a system hang caused by disabling edge gestures (credits to jenslody)
  * Themed All apps search bar on Launcher3 
  * Updated Links on Dumpster > About and also, removed G+ because that social network went to the same place our childhood puppy went,     hope both come back soon :(
  * Fixed a derp with the ShishuOTA overlay on Shishu Nights
  * Added missing permissions for Pixel/Devices without debug props for permissions.
  * Added some missing headers on OmniStyle
  * Fixed glitch on LS Filters for players like Phonograph, Black Player, etc, and also added 2 new effects, accent tinted cover art and     grayscaled + blurred cover art.
  
=====================
    29/03/2019
=====================
- Updated to March security patch
- Added /misc and /cache partition for OTA updater
- Added aptx and aptxhd codecs for bt audio
- Reflux Kernel R13:
  * Upstreamed to 3.18.137
  * Added Relaxed cpu governor
  * Added Maple io scheduler
- Synced with Bootleggers source (4.1):
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
  
=====================
    04/03/2019
=====================
- Merged February security update related to samsung source
- Added 2 more missing macloader mappings
- Fixed Bluetooth issues introduced with february security update 
- Misc performance and stability updates
- Synced with Bootleggers source
