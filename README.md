# v0rtex-injector beta 3

~~Get v0rtex with tweaks here: https://www.dropbox.com/s/s3yi19sth2hw09d/v0rtex-with-tweaks.ipa?dl=0~~ OLD VERSION
- ipa coming soon

- Only tweaks that hook springboard and don't use post installation/removal scripts will work

- you can't change preferences in settings. gotta do that manually (don't ask how)

- not a substrate replacement

- cydia is broken on purpose

- this is for devs & inpatient people

- ~~ssh is temporarily disabled (read the comments to see why)~~ Added SSH!

~~there's no safe mode or no-substrate mode, be careful what you install~~
- Added no-tweaks mode (NEW BETA 2) 

- to install find link to the deb file, run exploit, paste, click ok

- I've tested this multiple times and didn't encounter any bootloop but USE THIS AT YOUR OWN RISK. IT IS A BETA! The code should be fairly better now

- **INSTALLING TWEAKS SHOULD BE 100% SAFE, MY CONCERN IS EXTRACTING THE BOOTSTRAP, ONCE YOU GET THAT WORKING THR REST SHOULD BE OK.** postinst scripts do not run, all that will be done is injecting tweaks into SpringBoard. The worst is a respring loop that can be fixed by rebooting 

tweaks tested & confirmed working by me:

- Cylinder
- Sleek'n'bouncy 10
- DummyPass

not working:

- Zeppelin 
- anemone (PROBABLY)

Only some devices work: offsets will be added by time

Supported devices:

- 5S (10.3.1 - tested)
- 7 10.3.1 (not tested)
- SE 10.3.1 (not tested) (NEW IN BETA 2)
- 6S 10.3.1 (not tested) (NEW IN BETA 3)

TODO: install substrate properly, clean up symbols.m, use updated exploit, A WAY TO REMOVE TWEAKS, more devices

thanks to s1guza for exploit, stek29 for telling me how to get cydia work, cheesecakeufo for telling stek29 how to get cydia work, xerub for libjb, theninjaprawn for his techniques, PsychoTea for some other stuff, thisiswisy for hosting on his github & cleaning up code a little bit etc.

brought to you by Jake
