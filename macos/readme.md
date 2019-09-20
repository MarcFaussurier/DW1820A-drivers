I can confirm that the DW1820A BCM4350 14e4:43a3 1028:0023 (part # CN-08PKF4) 
is working like a charm on both windows and macOS

I managed to fix the problem that Herve reported on his tutorial mentioned on https://osxlatitude.com/forums/topic/11322-broadcom-bcm4350-cards-under-high-sierramojave/ ("several reports of issues (5-10mins Ok, then system freeze).") using a firmeware took from windows.

Copy / past all the kexts inside the Library/Extensions folder.

You must edit your clover config.plist in order to let your mac know you vendor id,
pc id and such.

To do so, follow the "Properties Injection though Clover config" section from the
nice Herve's tutorial on osxlatitude (https://osxlatitude.com/forums/topic/11322-broadcom-bcm4350-cards-under-high-sierramojave/)

Tesed under High Sierra, to be tested under Mojave soon.

