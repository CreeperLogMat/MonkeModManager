# Monke Mod Manager

This program will install custom mods into Gorilla Tag automatically, and can be re-run in order to update the mods

This uses the github api to get the latest release of all these mods, so you know you'll always be getting the latest version!

If you've made a mod that you want added to the installer, submit an issue including the label `mod addition request`

## To have your modded added
Include these details in the issue:
* The Github repository of the mod you want added 
* Any dependencies

Mod submission is likely subject to change in the future.

### Ensure that
* Your mod is built in the monke mod manager compatible format through `MakeRelease.ps1` (replace `netstandard2.0` with `netstandard2.1.0` in the code) or you use a DLL in your release
* You list the correct dependencies
* Your mod is fully working

## Questions and Ideas
You can submit any questions or ideas in `Discussions`
