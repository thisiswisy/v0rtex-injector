# v0rtex-injector beta 5

Get v0rtex-njector IPA here: https://github.com/thisiswisy/v0rtex-injector/releases/tag/b5

DEMO IMAGES: https://i.imgur.com/25jpFZN.jpg & https://i.imgur.com/D6dnjFj.png
-------------------------------------------------
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

- I've tested this multiple times and didn't encounter any bootloop ~~but USE THIS AT YOUR OWN RISK. IT IS A BETA! The code should be fairly better now~~. Others have tested as well. It is perfectly safe.

- **INSTALLING TWEAKS SHOULD BE 100% SAFE, ~~MY CONCERN IS EXTRACTING THE BOOTSTRAP, ONCE YOU GET THAT WORKING THR REST SHOULD BE OK.** postinst scripts do not run, all that will be done is injecting tweaks into SpringBoard. The worst is a respring loop that can be fixed by rebooting ~~. A respring loop can't happen because I am using modified killall binary instead of what substrate does. tweaks will load ONLY when you respring manually

tweaks tested & confirmed working by me:

- Cylinder
- Sleek'n'bouncy 10
- DummyPass
- Zeppelin (working as of b4)
- NoSlowAnimations

not working:

- anemone (may do something on the future as I had Anemone working when kppless was released for 10.2)

Only some devices work: offsets will be added by time

Supported devices:

- 5S 10.3-10.3.3 (tested)
- 6/6 Plus 10.3.1 (tested)
- 7/7 Plus 10.3.1 & 10.3.3 (not tested)
- SE 10.3.1 (not tested)
- 6S/6S Plus 10.3.1 - 10.3.3 (not tested)
- iPod Touch 6G 10.3.2 & 10.3.3 (not tested)
- More soon. DON'T ASK "WHEN" AND DON'T BEG "PLZ PLS"

TODO: clean up symbols.m, use updated exploit, A WAY TO REMOVE TWEAKS, more devices

thanks to s1guza for exploit, stek29 for telling me how to get cydia work, cheesecakeufo for telling stek29 how to get cydia work, xerub for libjb, theninjaprawn for his techniques, PsychoTea (and who worked on his project) for some other stuff, Wisy for hosting on his github & cleaning up code a little bit. 

Friendly message to /r/jailbreak:

- if you are concerned about my tool not being safe, check the code yourself, i am willing to help you compile it. I know nullpixel hates me, but his accusations are mostly false. I do not steal code (he says this because once I made a tool that did the same thing as his, he does not have proof I stole code), I do not release malware (he says this because once i released a proxy which AppleBetas removed from /r/sideloaded because he was afraid i could add malware, I did not do that). nullpixel, if you are reading this, I am willing to start from scratch, we should know each-other more, what do you think .-. I changed my thoughts about you since we talked in the jb discord, don't be shy, I know we can be friends :)

brought to you by Jake
