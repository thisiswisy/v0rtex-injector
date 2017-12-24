# v0rtex-injector beta 4

Get v0rtex tweak injector here: https://github.com/thisiswisy/v0rtex-injector/releases/tag/b4

- Only tweaks that hook springboard will work. postinst script should be fixed (beta 4 new)

- you can't change preferences in settings. gotta do that manually (don't ask how)

- not a substrate replacement

- cydia ~~is broken on purpose~~ now runs but DOES NOT INSTALL ANYTHING (beta 4)

- this is for devs & inpatient people

- ~~ssh is temporarily disabled (read the comments to see why)~~ Added SSH!

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

not working:

- anemone (PROBABLY)

Only some devices work: offsets will be added by time

Supported devices:

- 5S (10.3.1 - tested)
- 6 (10.3.1 - tested)
- 7 10.3.1 (not tested)
- SE 10.3.1 (not tested - experimental) (NEW IN BETA 2)
- 6S 10.3.1 (not tested) (NEW IN BETA 3)
- 6S 10.3.2 (not tested)
- 6S 10.3.3 (not tested - experimental)

TODO: clean up symbols.m, use updated exploit, A WAY TO REMOVE TWEAKS, more devices

thanks to s1guza for exploit, stek29 for telling me how to get cydia work, cheesecakeufo for telling stek29 how to get cydia work, xerub for libjb, theninjaprawn for his techniques, PsychoTea (and who worked on his project) for some other stuff, Wisy for hosting on his github & cleaning up code a little bit. 

Friendly message to /r/jailbreak:

- if you are concerned about my tool not being safe, check the code yourself, i am willing to help you compile it. I know nullpixel hates me, but his accusations are mostly false. I do not steal code (he says this because once I made a tool that did the same thing as his, he does not have proof I stole code), I do not release malware (he says this because once i released a proxy which AppleBetas removed from /r/sideloaded because he was afraid i could add malware, I did not do that). nullpixel, if you are reading this, I am willing to start from scratch, we should know each-other more, what do you think .-. I changed my thoughts about you since we talked in the jb discord, don't be shy, I know we can be friends :)

brought to you by Jake
