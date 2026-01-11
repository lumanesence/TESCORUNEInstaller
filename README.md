# TESCORUNEInstaller
A simple installer for i-win's TESCORUNE (DELTARUNE mod) written in Nullsoft Install System

##  What is it?
To put it really simply, TESCORUNEInstaller is an NSIS-generated .exe file used for installiing TESCORUNE (https://i-win.cc/tesco) onto your hard drive while also installing the mod into your AppData Roaming folder. 

## Has the mod istelf been modified?
**NO - the mod itself has not been modified in any way.** To prove this, I ran the mod through both RF Triage and AnyRun, which are both web apps designed to allow users to analyze what an executable file does. Below are the links to each analaysis:

- https://any.run/report/39d3d934c0a605398034f070bab5a109971b9e1502f1b60068016092866ad951/2824c0e5-93d6-47d3-8a6b-588b52d047d8
- https://tria.ge/260111-mtz19sht2h/behavioral1

Please note that the malicious activity mentioned in both of these reports is Kristal dropping it's own files into AppData. These too have not been modified and show no forms of malicious behaviour. Feel free to submit these files yourself if you so wish, and let me know via email what you find: t.hall2009@outlook.com. Since this app also installs to Program Files, C:\Program Files\The OneLyte Association\TESCORUNE to be exact, the installer will request for elevation.

## Can I build the installer myself?
Yes, the files that the installer uses to put on your hard drive are located within the root of this repository

## Credits
##### Copied from i-win's repo since I'm lazy
* Installer: Me! (Lumanesence)
* Mod: i-win (https://github.com/i-winxd/TESCORUNE/)
* Engine: https://kristal.cc
* Gaster Blaster lib - Scarm, JustAnotherRandomUser
* Yellow Soul lib - vitellaryjr
* Big Shot FLP - Nini
* Deltarune is made by Toby Fox and his team (obviously)
