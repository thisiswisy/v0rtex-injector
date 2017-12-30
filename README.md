# v0rtex-injector beta 7

Get v0rtex-injector IPA here (BETA 6): https://github.com/thisiswisy/v0rtex-injector/releases/tag/b6

DEMO IMAGES: https://i.imgur.com/25jpFZN.jpg & https://i.imgur.com/D6dnjFj.png

UPDATE:

My device bootlooped when trying a new bootstrap and I hadn't set a nonce (gotta wait for new tfp0 exploit, luckily it was a 5S I can downgrade once that happens, well by that time a full jailbreak will have been released anyway xd)

UPDATES will happen but not as frequently. I can't try new stuff to fix the activation issue anymore so I'll just focus on the jailbreakd damon. As of 30.12.2017 Injector uses a better method to find the proc without involving files and pidof. However I can't test it, although it should work just fine. A better jailbreakd which runs in a separate process is being worked on

----------------
NEW IN BETA 7:
1. Support for iPad Air 2, iPad Mini 3, iPad Mini 4, iPad Pro 10.5"
2. Added basic jailbreakd daemon (thanks cheesecakeufo)
3. Cydia can install *some* stuff

- Jailbreakd will only start with respring disabled
- once you quit the app jailbreakd STOPS and Cydia crashes

TODO:

- run jailbreakd in a separate process OR get a proper nosuid patch
- amfid patch (if you're impatient AND on ios 10.3-10.3.2 just run triple_fetch)
- something like PreferenceLoader
- more iPads

THERE'S NO IPA YET AND WON'T BE TILL EVERYTHING IS FIXED PROPERLY! NON-DEVS: DO NOT USE BETA 7

IF YOU USE BETA 7 DO NOT REINSTALL/REMOVE Cydia Substrate! IT *MAY* BREAK ALL OF YOUR TWEAKS

If you did that and tweaks stopped working, run this via SSH:

    rm /Library/MobileSubstrate/DynamicLibraries && mv /var/stash/*/*/DynamicLibraries /Library/MobileSubstrate/DynamicLibraries
    
- Respringing via Cydia will unload all of your tweaks

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
- iMessage not working

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
-------------

HOW TO COMPILE???

If you're using Xcode 9:
1. Open Xcode from an admin account
2. Find any line where system() is mentioned
3. CMD + click on system() -> go to definition
4. Remove the "IOS_PROHIBITED" line or something like that and save the file

-------------------------------------------------

HOW TO FIND DEB LINK????
- This gives you **LEGAL** debs straight from their original sources: http://ipod-touch-max.ru/cydia/index.php?cat=search&keyword=YOUR_TWEAK_NAME_HERE

What is this? 
- Something that lets you install tweaks on iOS 10.3.x

- Only tweaks that hook springboard will work. postinst scripts should be fixed (beta 4 new)

- you can't change preferences in settings. gotta do that manually (don't ask how)

- not a substrate replacement

- this is for devs & inpatient people

- SSH via USB on port 2222

- no-tweaks mode 

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


Supported devices:

- ALL iPhones, iPods on 10.3-10.3.3
- Some iPads (NO IPA YET!)



thanks to s1guza for exploit, stek29 for telling me how to get cydia work, cheesecakeufo for telling stek29 how to get cydia work, xerub for libjb, theninjaprawn for his techniques, PsychoTea, Sticktron (and who worked on his project) for some other stuff, Wisy for hosting on his github & cleaning up code a little bit. 

- Forked from an older version of this: https://github.com/PsychoTea/v0rtex-S
- Got cydo binary from an older version of this: https://github.com/iabem97/topanga
- Got jailbreakd idea from this: https://github.com/iabem97/topanga
- Got a lot of techniques from this: https://github.com/ninjaprawn/
- Got amfi patch from this: https://github.com/xerub/extra_recipe/tree/kppless

Mr.Cryptiic: happy now?

------

brought to you by Jake
