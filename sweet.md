## 1.8 Sweet/Sweetin
- Updated blobs from MIUI V13.0.8.0.SKFMIXM
- Update adreno from LA.UM.9.1.r1-11500.02-SMxxx0
- Switched to EROFS (Enhanced read only file system)
- Enabled F2FS compression (Needs a clean flash to work)
- Added Moto Dolby with a tuned configuration from MIUI on the Redmi Note 10 Pro (Thanks helenius147)
- Optimize native executables for Cortex-A76 CPU
- Switch to dot product CPU variant
- Improved vibrations
- Nuked Vulkan (due to some heating/drain)
- Fixed the remaining stuff in miuicamera like clone mode (thanks to Adarsh) P.S. slow-mo is still dead
- Updated VantomKernel and PlayGround clang
- Other misc. changes

## 1.7 Sweet/Sweetin
- Switched to Arian's common tree
- Updated blobs to MIUI V13.0.8.0.SKFEUXM
- Update GPS from LA.UM.9.1.r1-11800-SMxxx0.0
- Fixed aptX and aptX HD
- Fixed IR blaster
- Fixed issues with the status bar
- Slightly increased the status bar height (to how it was on older builds)
- Fixed some more issues with camera
- Fixed the fingerprint wake-up animation
- Fixed the low-mic issues that some people had using a few apps
- Fixed WiFi Display (Miracast)
- Fixed some issues with dirac
- Improved vibrations
- Removed HBM for now due to issues with brightness
- Updated vibration patterns
- Updated deprecated screen power items
- Added a few missing blobs
- Misc. fixes and changes

## 1.6 Sweet/Sweetin
- Sync main display cutout from stock
- Set an overlay to indicate power button FPS
- Disable slow blur effect to avoid laggish blur effect
- Add night display color temperature calibration from Coral
- Add KeyHandler for side-mounted fingerprint key
- overlay: Set physical button/sensor locations
- Define OEM fast charge sysfs node
- decrease status bar top padding value
- Add front-facing camera protection
- devicesettings: Fix "dirac_hifi_enable_title" string
- Reduce screenshot delay to 0
- Configure side fingerprint sensor properties
- Nuke CutoutRingService
- Expose aux camera globally
- Configure side fingerprint sensor properties
- Allow every app to read camera props
- Disable QTI perf lock usage in camera HAL
- Add dirac QS tile
- Address some sepolicy denials
- Introduce haptic feedback level adjustment
- Add MiSound scenes
- Improve Xiaomi Parts icons
- Add KCAL
- Update build fingerprint from Raven -SP2A.220405.004/8233519 For April SPL
- Introduce FPS counter QS Tile
- Update side Fingerprint location
- Update s5kgw3 camera blobs from sweetin miui13 A12 beta release
update vendor security patch level from (sweet-user-12-SKQ1.210908.001-V13.0.2.0.SKFMIXM-release-keys)

## 1.5 Sweet
- Updated blobs from MIUI 13 v13.0.2.0 Global
- Fixed OK Google
- Updated GPS to LA.UM.9.1.r1-11500-SMxxx0.0
- Fixed OTA updates
- Switch to Sleepy Kernel

## 1.4 Sweet

- initial build by me (zaidkhan0997)
- ventom kernel prebuild
- enforcing and user build 
- deep sleep issue fixed 
- oss vendor based build

## 1.2 Sweet

- Switch to CamerGo Gretness Special
- Switch to Vantom Kernel
- Allow more cached apps in the background
- Use Monet colors for power menu
- uprev android.hardware.health hal to 2.1
- Rebrand DeviceSettings
- Added Notch Bar Killer (Under Developer Options/Device Cutout)
- Latest Vantom Kernel
- Import HotwordEnrollment from OnePlus 8 Pro (Faster OK Google)
- Cleanup some cleanup powerhint
- Games Max FPS Added to source
- Google Dialer Call Recording Works

## 1.1 Sweet

- Enforcing Build
- Fixed OK Google (Hey Google Works)
- Fixed Google Voice Recorder
- Fixed USB OTG issues
- Fixed Sdcard issue
- Added Turbo charging" instead of "Charging rapidly"
- Added Google CameraGo
- Many underhood changes
- Fixed UI Lags,Shutters etc issue
- Fixed audio bug on some apps like MS Teams
