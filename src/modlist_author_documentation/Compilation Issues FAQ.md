# Compilation Issues FAQ

This page is and will always be in development and update over time.

## Mod Organizer Setup Issues

### Portable Instances

> **Setup a Portable Instance:**
>
> Start by downloading `Mod.Organizer-X.X.X.7z` ("x.x.x" will be the latest version number) and extract it to a folder.  
> Start the `ModOrganizer.exe` follow the first time setup tool to create a portable instance for the game you want to mod.
>
> Navigate to the `downloads` folder and paste the `Mod.Organizer-X.X.X.7z` into there and create a `Mod.Organizer-X.X.X.7z.meta` containing the following text:
>
> ```ini
>  [General]
>  installed=true
>  directURL=https://github.com/ModOrganizer2/modorganizer/releases/download/vX.X.X/Mod.Organizer-X.X.X.7z
> ```
>
> *Replace `X.X.X` with the correct version number.*
>
> **Importing a Global/Pseudo Portable Instance into a Portable one:**
>
> If you have your Portable Instance ready then go to your Global/Pseudo Portable Instance and copy the `profiles`, `mods`, `downloads` folders and paste them into your Portable instance.

## Error Codes

### Failed Compilation: Can't find game Morrowind

> **You are trying to compile a Modlist for Morrowind:**
>
> Something with the game detection is broken, please join the discord for more direct help identifying the issue.
>
> **You are trying to compile a non Morrowind Modlist:**
>
> You are using a Pseudo Portable instance and need to [convert it to a portable one](#portable-instances).

### Cannot find source for .meta files

> **The sourced downloads folder is inside of MO2.**  
> Place it outside MO2 so you can name it however you want.  
> Example of how to do it: D:\WJ Downloads\{list_name} with the list being D:\WJ Projects\{list_name}  
> (list_name doesn't need to be the same name, it is just an example.)  

> **If you want to keep it inside of MO2;**  
> Use the compiler settings to tell Wabbajack to ignore the renamed downloads folder if you want a custom folder name and the folder present inside the MO2 location.
