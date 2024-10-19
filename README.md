# Future Proof PC Console - Issues

### Be sure to read the other guides named fp-pc-console-*

## Booting from different computers

Going from Intel graphics to AMD graphics means you'll need to install those drivers with apt.

Also, you may need to use System Rescue CD/DVD/USB to fix the Grub efi stuff.

And I noticed that the audio wasn't playing, so I had to change that in the audio selector in xfce.  Then I opened up the xfce audio mixer from the little icon, and chose the HDMI one as the fallback.  I think this totally fixed the issue.  If that doens't work, i could just disable the extra audio interfaces in bios.

Also, depending on how strong your computer is, you'll need to change the settings for your pcsx2 emulator. 
I do per game settings by hitting the home button, and going down to the "copy settings" or "clear settings" to remove them.  It can be a little confusing since it doesn't really give you any warning that you are using per game settings.

### Be sure to read the other guides named fp-pc-console-*
