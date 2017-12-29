#################################################################
+++  Dell T1700 BIOS Updater - Skip device check Patch
#################################################################
|                                                               |
 \                                                             /
  | Release Date......: 30th December 2017                    |
  | Type..............: Application                           |
  | Platform..........: Windows                               |
  | Includes..........: Patch only                            |
  | Website...........: https://www.dell.com                  |
  | Parts.............: 1x651.280 bytes                       |
  | Compression Type..: ZIP                                   |
  | File Validation...: SFV                                   |
  | Protection........: Device check                          |
 /                                                             \
|                                                               |
#################################################################
+++  Release Info
#################################################################
|                                                               |
 \                                                             /
  | ATTENTION!                                                |
  |                                                           |
  | You may brick your device if you use this patch to        |
  | install a non fitting BIOS.                               |
  |                                                           |
  | Tested with version A21 (T1700A21.exe)                    |
  |                                                           |
  | Skips the device check in every Dell BIOS Updater.        |
  | Tested on the Dell T1700 (0x05a6) BIOS                    |
  | to use it on the Dell T20 (0x0620).                       |
  |                                                           |
  | You may void your warranty!                               |
  |                                                           |
  | Replaces the CMP EAX, 2 with CMP EAX, 1.                  |
  |                                                           |
  | source:                                                   |
  | https://www.hardwareluxx.de/community/f101/dell-poweredge-t20-1031138-143.html#post24890390
 /                                                             \
|                                                               |
#################################################################
+++  About
#################################################################
|                                                               |
 \                                                             /
  | Thx 2 tolga9009 @hardwareluxx.de for providing the        |
  | initial patch via ollydbg                                 |
  |                                                           |
  | skin created by kruzco @tuts4you URET Skin Graffiti       |
 /                                                             \
|                                                               |
#################################################################
+++  Install Notes
#################################################################
|                                                               |
 \                                                             /
  | 1. Extract "dell.t1700.bios.updater-patch.exe"            |
  | 2. Run the "dell.t1700.bios.updater-patch.exe"!           |
  | 3. Press "Patch" button!                                  |
  | 4. Select BIOS Update file (ex. T1700A21.exe)             |
  | 5. Update BIOS (you may remove the PSWD jumper)           |
  | 6. Enjoy                                                  |
 /                                                             \
|                                                               |
#################################################################