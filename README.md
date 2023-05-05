# Windows10GamingFocus
This is A FORK Based On ChrisTitusTech that's foucus on debloat and optimize windows 10/11 for the lowest latency and best gaming experience, the Ultimate Windows 10/11 Script is a creation from multiple debloat scripts and gists from github. I also added Chocolatey and other tools to the script that I install on every machine.
```
Warrning: I am NOT responsible for what you do to your Devices/Systems, so follow these instructions at your own risk. Make sure you know what you're doing, it's best to understand the process rather than just copy and paste commands and such.
```

## Changelog!

## Modifications
I encourage people to fork this project and comment out things they don't like! Here is a list of normal things people change:
- Uninstalling OneDrive (This is on in my script)
- Installing Adobe, Chocolatey, Notepad++, MPC-HC, and 7-Zip

Comment any thing you don't want out... Example:

```
########## NOTE THE # SIGNS! These disable lines This example shows UACLow being set and Disabling SMB1
### Security Tweaks ###
	"SetUACLow",                  # "SetUACHigh",
	"DisableSMB1",                # "EnableSMB1",

########## NOW LETS SWAP THESE VALUES AND ENABLE SMB1 and Set UAC to HIGH
### Security Tweaks ###
	"SetUACHigh",
	"EnableSMB1",
```
