# v0rtex-injector beta 7

Get v0rtex-injector IPA here (BETA 6): https://github.com/thisiswisy/v0rtex-injector/releases/tag/b6

DEMO IMAGES: https://i.imgur.com/25jpFZN.jpg & https://i.imgur.com/D6dnjFj.png
----------------
NEW IN BETA 7:
1. Support for iPad Air 2, iPad Mini 3, iPad Mini 4, iPad Pro 10.5"
2. Added basic jailbreakd daemon (thanks cheesecakeufo)
3. Cydia can install *some* stuff

- Jailbreakd will only start with respring disabled
- once you quit the app jailbreakd STOPS and Cydia crashes

TODO:

- run jailbreakd in a separate process
- amfid patch (if you're impatient AND on ios 10.3-10.3.2 run triple_fetch)

THERE'S NO IPA YET AND WON'T BE TILL EVERYTHING IS FIXED PROPERLY! NON-DEVS: DO NOT USE BETA 7
-----------------------------------
NEW IN BETA 6:

1. Even more devices
2. exploit updated, now more reliable
3. tried to fix ~~Fixed~~ the activation screen issue
4. hopefully fixed the respring panic issue on A9 devices
5. you can now load tweaks without respring (only some will work properly) and with a different method (again - only some will work properly - for compatibility issues with Method 1)
-------------------------------------------------

KNOWN ISSUES:

- Activation screen each reboot

Possible fixes:
1. Reset All Settings
2. Reset All Contents & Settings
3. Disable passcode


NEW IN BETA 5:

1. More devices
2. tweaks load properly
3. bootstrap extracts properly
4. bug fixes
5. added "reset jailbreak" option. use this if you have any issues
-------------------------------------------------
TODO:

1. Make cydo run as root (so Cydia works)
2. Make something like PreferenceLoader within the app itself (so you can change settings)
3. More devices
4. amfid patch
5. ??
----------------------------------------

HOW TO FIND DEB LINK????
- This gives you **LEGAL** debs straight from their original sources: http://ipod-touch-max.ru/cydia/index.php?cat=search&keyword=YOUR_TWEAK_NAME_HERE

What is this? 
- Something that lets you install tweaks on iOS 10.3.x

- Only tweaks that hook springboard will work. postinst scripts should be fixed (beta 4 new)

- you can't change preferences in settings. gotta do that manually (don't ask how)

- not a substrate replacement

- cydia ~~is broken on purpose~~ now runs but DOES NOT INSTALL ANYTHING (beta 4)

- this is for devs & inpatient people

- ~~ssh is temporarily disabled (read the comments to see why)~~ Added SSH! (BETA 2)

~~there's no safe mode or no-substrate mode, be careful what you install~~
- Added no-tweaks mode (NEW BETA 2) 

- to install find link to the deb file, run exploit, paste, click ok. If you want to just activate current tweaks click ok without entering any link

- I've tested this multiple times and didn't encounter any bootloop. Others have tested as well. It is perfectly safe.

- **INSTALLING TWEAKS IS 100% SAFE, A respring loop can't happen because I am using modified killall binary instead of what substrate does. tweaks will load ONLY when you respring manually** THIS TOOL IS ON BETA 6 SO FAR AND IS NOT DANGEROUS IN ANY WAY. WILL NOT INTERFERE WITH NEW JAILBREAKS.

tweaks tested & confirmed working by me:

- Cylinder
- Sleek'n'bouncy 10
- DummyPass
- Zeppelin (working as of b4)
- NoSlowAnimations
- RoundDock

not working:

- anemone 

Only some devices work: offsets will be added by time

Supported devices:

- ALL iPhones, iPods on 10.3-10.3.3
- Some iPads (NO IPA YET!)



thanks to s1guza for exploit, stek29 for telling me how to get cydia work, cheesecakeufo for telling stek29 how to get cydia work, xerub for libjb, theninjaprawn for his techniques, PsychoTea, Sticktron (and who worked on his project) for some other stuff, Wisy for hosting on his github & cleaning up code a little bit. 


brought to you by Jake
