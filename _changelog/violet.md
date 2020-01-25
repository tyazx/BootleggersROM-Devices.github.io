---
codename:violet
---
=====================
    23/01/2020
=====================

Device Changes:
- Inline firmware and custom modem.
- Reduced touch latency
- a bunch of other stuff (check the trees)

ROM Changes:
- Initial stable 10 release
- Added UI Styles and Screen recorder with internal audio support
- Launcher3 tweaks: Icon packs, at a glance, a dark mode friendly google panel
- Material toasts
- Suspend actions
- Power menu options and disable on secured lock
- QS columns and rows
- Network indicator with OOS style (thanks ArrowOS)
- Pulse on new tracks and ambient visualizer
- Lockscreen cover blur and our silly filters
- Toggle brightness slider, auto brightness icon
- Show running services and even our custom footer text instead of the build info (you can make your own too)
- Vibrate on tapping QS tiles
- 3 Fingers to screenshot
- Headsup with all those tweaks
- Fingerprint tweaks like error vibration and all that jazz
- OmniJaws for weather (because it's reliable even on a non-gapps scenario)
- OmniStyle with our header spicy selection, and also, a bug fix for 4K images that made the SystemUI crash and burn
- Maybe some more things

=====================
    21/09/2019
=====================

Device Changes:
- Enforce SElinux
- Upstream kernel to 4.14.145
- Update blobs from laurel_sprout
- Drop Dirac
- Include LiveDisplay

ROM Changes:
- Gaming Mode v2 -Now with roblox support-
- Fixes for QS detailed view
- Advanced location enabled
- Added support for Pixel stand
- Updated some boost framework stuff
- Adding cutout force full screen
- Shishu Launcher Free with a premium upgrade added
- Added LiveDisplay
- Force powersave on system apps
- New intro for new devices
- Moving net indicator to expanded statusbar header
- Fixes for Q clock strings
- Long screenshot
- Internal Audio recording
- New launcher quickspace stuff: Adding now playing -even though it's not fully compatible-, Personality (taken from lawnchair) and a new UI, more minimalistic
- Fixed the inverted navbar layout
- People actually fell off thinking that Shishu Launcher Premium was a thing, so we reverted that joke on our changelog
- Switched to Lineage Fingerprint on Display code
- Added support for sliders for OP devices
- Added some goofy stuff: like The Drill and Developer mode insulter
- Updated our APNs
- Fixed dialer dark numbers on numpad
- Misc fixes
- Removed Roblox as system app

=====================
    11/08/2019
=====================

NOTE: You need 9.7.18 or higher firmware before flashing this build

Device Changes:
- Enable WIFI Aware
- Import SVI configuration
- rootdir: Override vendor.hwcomposer-2-2 service definition
- Reformat fingerprint rc file
- Set prop expected by the FM radio HAL
- Remove more obsolete system properties
- Drop the creation of deprecated system_data folders
- Add QC location support
- gps: Disable xtwifi* services
- Update vendor blobs from davinci
- Uprev vendor.display.config to 1.7
- Update vendor CarrierConfig from MIUI 9.7.11
- Import missing learning module blobs
- configs: Adding min freq of 1.2Ghz for 480fps
- Move powerhint.xml from vendor tree to device tree
- Enable full dexpreopt
- Enable AAC frame control for A2DP
- Remove wcnss_filter and all references to it
- releasetools: be more clear about firmware image patching
- Update Graphics stack from ZenFone 6
- Update DRM stack from davinci
- Drop useless color mode support
- Use oneplus 7 vibration pattern
- Add QCOM's WFD implementation
- Remove deprecated cmdline option
- Move init.qti.charger.sh to bin
- Cleanup usb shell script
- Enable audio features for sound FX libraries
- Enable TARGET_USES_DISPLAY_RENDER_INTENTS
- Copy media_codecs_google_video_le from fw/av
- Set SSR restart_level in init.qcom.rc
- Include missing OMX blobs
- Force fw from MIUI 9.7.18 and up
- Configure old talosAU SKU parameters same as 6155P
- Update GPS HAL to LA.UM.7.9.r1-07800-sm6150.0
- Update baseband assertion info
- Build libaudioroute
- Update IFAA for pie blobs
_ Kernel changes

=====================
    13/07/2019
=====================

Device Side Changes
- Parts: Migrate to androidx
- Add QPerformance and UxPerformance jars
- Compile kernel with clang 9.0.5
- Camera: Hack focus modes
- Add missing media blobs
- Import media properties XML from LA.UM.7.9.r1-07500-sm6150.0
- Update gps config from caf
- Build some soundfx from source
- Bring back WMA
- Restore stock bluetooth HAL

ROM Side Changes:
- July Security Patches

=====================
    01/07/2019
=====================

Device Side Changes
- Update blobs to MIUI 9.6.27
- Drop goodix firmware
- Update Build fingerprint to V10.3.9.0
- Enable OEM unlocking option
- Add Vector icons to Xiaomi Parts
- Update rootdir/configs from caf
- Drop prebuilt media HAL
- Partially  build display HAL
- Force VoLTE on supported carriers
- Update GPS HAL to  LA.UM.7.9.r1-07300-sm6150.0
- Enable 4k recording on front cam
- Use Studio Thermal Profile for camera
- Address Camera lags
- Improved signal reception
- Build context hub / qti camera device
- Add Dirac Sound Control

=====================
    13/06/2019
=====================

NOTE:- Before doing an OTA you need to read https://t.me/keepthebootlegviolet/626

Device Side Stuff
* Rebased to GuaiYiHu's Trees
* Vendor is now built inline
* Blobs updated from Redmi K20
* Supports proper System as Root mounting
* Other changes

ROM Side Stuff
* ROM version bump to 4.2
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
    12/05/2019
=====================

Device Side Stuff
* Updated panel FW (fixes touch delay) thanks to @TheScarastic
* Included dtbo

ROM Side Stuff
* Enabled Notch city from POSP
* Source upstream

=====================
    10/05/2019
=====================

NOTE: You have to flash stock vendor image from miui and fcrypt disabler zip before OTA or seeya bois in fastboot. Check @keepthebootlegviolet for more details

Device Side Stuff
* Added VDSO
* Fixed IR Blaster
* Fixed D2TW not working in some cases
* Fixed notification led not working in some cases
* Updated power hal

ROM Side Stuff
* Merged May Security Patches

=====================
    03/05/2019
=====================

* Actually fix Preferred Network FC.

=====================
    03/05/2019
=====================

* Intial Build
* Preferred Network FC has been fixed
