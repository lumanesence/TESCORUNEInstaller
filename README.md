# TESCORUNEInstaller
A simple installer for i-win's TESCORUNE (DELTARUNE mod) written in Nullsoft Install System

##  What is it?
To put it really simply, TESCORUNEInstaller is an NSIS-generated .exe file used for installiing Kristal (the launcher that TESCORUNE uses) onto your hard drive while also installing the TESCORUNE mod itself into your AppData Roaming folder. 

## Has Kristal or the mod istelf been modified?
**NO - neither Kristal or the mod itself has not been modified in any way.** To prove this, I ran the file through both RF Triage and AnyRun, which are both web apps designed to allow users to analyze what an executable file does. Below are the links to each analaysis:

- https://any.run/report/39d3d934c0a605398034f070bab5a109971b9e1502f1b60068016092866ad951/2824c0e5-93d6-47d3-8a6b-588b52d047d8
- https://tria.ge/260111-mtz19sht2h/behavioral1

Please note that the malicious activity mentioned in both of these reports is Kristal dropping it's own files into AppData. These too have not been modified and show no forms of malicious behaviour. Feel free to submit these files yourself if you so wish, and let me know via email what you find: t.hall2009@outlook.com. Since this app also installs to Program Files, C:\Program Files\The OneLyte Association\TESCORUNE to be exact, the installer will request for elevation. As per usual with NSIS, you can customise where it gets installed

## Can I build the installer myself?
Yes! - the files that the installer uses to put on your hard drive are located in the "DIY.zip" under each release

### Building the installer
1. Download and install NSIS from https://nsis.sourceforge.io/Download
2. Open NSIS and click on "Compile NSI Scripts"
3. Download the "DIY.zip" file from the latest release, and extract it
4. Witin the "MakeNSISW" window, go to File -> Load Script (or press CTRL+L)
5. Select the "tescorune.nsi" file
6. Compile the installer by pressing CTRL+R

You may also make any modifications to this installer and publish it as such, making sure you credit both me and i-win when doing so

## Credits
##### Copied from i-win's repo since I'm lazy
* Installer: Me! (Lumanesence)
* Mod: i-win (https://github.com/i-winxd/TESCORUNE/)
* Engine: https://kristal.cc
* Gaster Blaster lib - Scarm, JustAnotherRandomUser
* Yellow Soul lib - vitellaryjr
* Big Shot FLP - Nini
* Deltarune is made by Toby Fox and his team (obviously)

## DISCLAIMER
Both the mod and installer are provided as-is without any warranties or guarantees. 

*Copyright 2026 The OneLyte Association. All rights reserved*
