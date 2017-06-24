# AospExtended 4.3 for Oneplus 3/3T!

# Weekly Build 3 of June!
**[24.06.17]**

- op3: Remove BCL hotplug disable/enable from init
- IPACM: fix security issue in querying if index 
- Re-enable delete_aiding_data for user build 
- IPACM: fix the security issue in ConntrackClient
- ipacm: fix the heap-use-after-free issue on bootup
- op3: Restore original CAF gps configuration 
- op3: Adjust lmk parameters
- op3: Update from Open Beta 18 
- op3: Convert rf_version to integer before comparison 
- op3: Update qti telephony extension from MIUI 7.6.5 dev
- op3: Grant netmgrd proper unix perms 
- op3: Drop NET_RAW and NET_ADMIN from qti
- op3: rmt_storage should have wakelock GID
- op3: Add system GID to rmt_storage
- Revert "op3: sepolicy: Fix rmt_storage and rfs_access policies" 
- op3: sepolicy: Remove old and duplicate permissions
- op3: Define ril-daemon normally 
- op3: Sync bluetooth configuration with CAF
- op3: Add Oneplus Cam to hal1 package List 

# Note:-
- Recommended to flash on OOS OB18/OB9 OP3/3T firmwares.
- Rootless Build. Flash your choice of root!


**[15.06.17]**

- oneplus3: Update from OxygenOS 4.1.5 
- oneplus3: Update ril header for 7.1.2 
- oneplus3: update power profile 
- oneplus3: Switch to DSP Audio Effects!
- Revert "oneplus3: remove highspeed recording profiles"
- oneplus3: Fix Pocket Mode service
- oneplus3: Build Back OneplusPocketMode
- oneplus3: Fix Doze
- oneplus3:Build back OneplusDoze
- oneplus3: Update to 4.1.5 OOS Blobs

# Note:-
- Recommended to flash on OOS 4.1.5 firmwares.
- Rootless Build. Flash your choice of root!

**[08.06.17]**

- Kicked OOS apps (Camera and Gallery) 
Can be downloaded separately from @siankatabg's thread... no need of including prebuilts and bloating the build!
- OnePlus Gestures are now moved to Settings > Gestures > Device Gestures! I wasnt liking the two spammy gestures options! Looks more 
clean!
- Re-enable delete_aiding_data for user build 
- op3: Update Adreno firmware checksums for Open Beta 8/17 @sultanxda
- op3: Doze: Require non-wake up proximity sensor
- init.qcom.rc : Add time_daemon in init.qcom.rc
- op3: rootdir: Update fs tune from marlin
- op3: Use kryo 32-bit routines 
- op3: Set camera package name to OnePlus Camera
- op3: Add specific camera parameter library 
- op3: Remove camera shim library
- op3: Update to OB16 blobs
- EAS Optimizations
- PA optimizations
- Improvements on Idle Drains
- Changed EAS values for better performance and battery!

# SNAP CAM Changelog

- Snap: Make video quality helpers aware of time-lapse mode
- Snap: Bypass focus state checks in doSnap() for the front camera 
- Snap: Silence face detection log spam

# Note:-
- Recommended to flash on OB8/OB17 firmwares.
- Rootless Build. Flash your choice of root!
