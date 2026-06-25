# Square Sound MEIZU 21 Note Magisk Module

## DISCLAIMER
- MEIZU apps and blobs are owned by MEIZU™.
- The MIT license specified here is for the Magisk Module only, not for MEIZU apps and blobs.

## Descriptions
- Equalizer sound effects ported from MEIZU 21 Note (Meizu21Note) and integrated as a Magisk Module for all supported and rooted devices with Magisk
- Global type sound effect
- THERE IS NO APP ICON IN HOME SCREEN
- YOU NEED TO OPEN MusicFX APP VIA Equalizer OPTION IN YOUR MUSIC APP SETTINGS

## Sources
- https://dumps.tadiphone.dev/dumps/meizu/meizu21note qssi-user-14-UKQ1.230917.001-1711913844-release-keys
- system_9: https://dumps.tadiphone.dev/dumps/meizu/meizu16spro meizu_16sPro_CN-user-9-PKQ1.190616.001-1572446663-release-keys
- libmagiskpolicy.so: Magisk (stable) 30.7 (30700)

## Changelog

v1.2
- Support NoMount metamodule
- Update libmagiskpolicy.so from Magisk (stable) 30.7 (30700)
- Resets module folders/files permissions at post-fs-data
- Move _uninstall.log to /data/adb/logs/
- Removes conflicted weird modules
- Does not disable raw playback (You can use Audio Compatibility Patch Reborn Magisk Module instead)

v1.1
- Fix wrong target in latest KernelSU
- Improve detections

v1.0
- Abort installation if fail to mount mirror system
- Tidy up aml.sh
- Exclude \*audio\*effects\*haptic\*.xml
- Fix wrong file permissions in some ROMs

v0.9
- Improve /odm and /my_product support detection

v0.8
- Fix a crash

v0.7
- Add Action button to clear apps caches
- Fix architecture detection in some weird ROMs
- Fix bug in uninstall.sh

v0.6
- Does not require FlymeMusic.apk
- Fix headphone not detected

v0.5
- Allow installation in Android Emulator
- Fix architecture detection

v0.4
- Add missing permission QUERY_ALL_PACKAGES

v0.3
- Fix AUDIO64BIT detection while installing via recovery in Android 9 if Magisk installed

## Screenshots
https://t.me/ryukinotes/18

## Requirements
- Android 10 (SDK 29) and up in arm64-v8a or armeabi-v7a architecture with HIDL audio service
- Android 9 (SDK 28) in armeabi-v7a or arm64-v8a with armeabi-v7a support architecture with 32 bit HIDL audio service
- Magisk or Kitsune Mask or KernelSU or Apatch installed
- Earphone/headphone connected

## Installation Guide & Download Link
- If you are using KernelSU, you need to disable Unmount Modules by Default in KernelSU app settings and install https://github.com/KernelSU-Modules-Repo/meta-overlayfs or https://github.com/KernelSU-Modules-Repo/magic_mount_rs or https://github.com/KernelSU-Modules-Repo/hybrid_mount or https://github.com/maxsteeel/nomount first depending on ROM compatibility
- Install this module via Magisk app or Kitsune Mask app or KernelSU app or Apatch app or Recovery if Magisk or Kitsune Mask installed and download FlymeMusic.apk
- Install AML Magisk Module https://t.me/ryukinotes/34 only if using any other else audio mod module
- Reboot
- If you are using KernelSU, you need to allow superuser list manually all package name listed in package.txt (and your home launcher app also) (enable show system apps) and reboot afterwards
- If you are using SUList, you need to allow list manually your home launcher app (enable show system apps) and reboot afterwards
- OPEN MusicFX APP VIA Equalizer OPTION IN YOUR MUSIC APP SETTINGS
- Connect your earphone/headphone

## Optionals
- Global: https://t.me/ryukinotes/35
- Stream: https://t.me/ryukinotes/52

## Troubleshootings
Global: https://t.me/ryukinotes/34

## Support & Bug Report
- https://t.me/ryukinotes/54
- If you don't do above, issues will be closed immediately

## Credits and Contributors
- @HuskyDG
- https://t.me/viperatmos
- https://t.me/androidryukimodsdiscussions
- You can contribute ideas about this Magisk Module here: https://t.me/androidappsportdevelopment

## Sponsors
https://t.me/ryukinotes/25


