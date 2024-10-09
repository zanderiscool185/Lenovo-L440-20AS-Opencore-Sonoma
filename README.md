This repo contains a EFI for installing the BEFORE and AFTER of the macOS install for Sonoma (macOS 14)
the first Boot/Install EFI contains Opencore version 0.8.8, which only DMG loads the first phase (ONLINE INSTALL PLEASE USE ETHERNET AS WIFI IS NOT ENABLED)

the PostInstall EFI contains opencore V0.9.9 as of the last sucessful boot, the minimum opencore version needed to boot macOS Ventura (13) is 0.8.4 and the version needed to boot macOS Sonoma is 0.9.4 (or higher preferably)

the SMBIOS for those using this repo as a reference point should stick to MacBookPro15,1 (please double check the spelling as i may have typed it wrong and macOS is case-sensitive)

also shoutout to the crew of this fantastic repo for supporting the WiFi cards, as well as linking a guide to fix iServices
https://github.com/OpenIntelWireless/itlwm

FAQ
Q: oh sh!t, my graphics are broken! what do i do?
A: OOB graphics were dropped in macOS Monterey (macOS 12), so you'll need to use Opencore Legacy patcher -> Post-install Root Patches -> it should pop up saying "Intel HD graphics Haswell" and if you are using the provided EFI, SIP and apples AMFI are already disabled, re-enabling SIP breaks backlight controls among other things, enable SIP at YOUR OWN RISK

FYI i actually used a fellow users premade efi also here on github, but that was for monterey, hasnt been touched since, so hopefully this helps someone in the future!
PS, his github repo with the EFI i used/updated is located here! shoutout to them! https://github.com/alerion921/Lenovo-Thinkpad-L440-20AS-OpenCore
SMBIOS he used was MacBookPro13,3

this is probably the last macOS version that will run on this hardware, as its starting to show the age and lag
SSD is STRONGLY RECCOMMENDED

i started hackintoshing with Mac OS X Mavericks (10.9) and have loved it ever since, maybe its time to let go of this old hardware
GodSpeed fellow hackintoshers
and best of luck! HAPPY HACKING!
