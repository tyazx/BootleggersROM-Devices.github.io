---
title:hero2lte
layout:changelayout
---
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
