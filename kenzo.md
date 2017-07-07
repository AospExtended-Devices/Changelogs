# AospExtended 4.4 for kenzo! [7/7/17]

- Remove modem assertion check
- Implement DT2W in settings
- Update all blobs (except camera, as we have different sensor) from MIUI Nougat for Hydrogen
- Update power configurations
- Remove the extra props for HWUI
- Add and update Snap overlay
- Fix camera memory leaks, buffer overflow, camera-daemon crash, ZSL issue in OSS HAL
- Disable ZSL in Snap camera by default for good.
- Merge latest CAF tag in kernel
- Merge latest WiFi driver in kernel
- Add latest CVE patches
- Add back SultanXDA patch for safetynet
- Implement proper locking of Ping in kernel
- Fix memory leaks of camera actuator
- Switch to my own version of Snap camera

_From now on I'll be  shipping this ROM with my own Snap camera. It contains fixes from LOS, CAF and from Billchen's repo._
