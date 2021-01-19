# Guide To Switch Emulation
This Repo explains how to install the yuzu Switch Emulator without a Switch on a Windows PC, If you use anything out of this please credit me appropriately!

[![Discord](https://img.shields.io/discord/622504866132000768?logo=Discord)](https://discord.gg/8KMuRMx)

  # Quick Links
  * [yuzu-Setup](#setup)
   * [Needed-Files](#files)
   * [Settings](#settings)
   * [Games](#games)
    * [GameCart-Dumping](#gamecart-dumping)
  * [Additional](#additional)
   * [Compatability](#compatibility) 
   * [GameUpdates](#gameupdates)
   * [BCAT](#bcats)
   * [Mods/Patches](#addons)
  * [Goodbye](#goodbye)

  ## Setup
 First you will need [yuzu](https://pineappleea.github.io/).
 Download it.
 Open it in WinRar, 7ZIP idk and then move the contents in a folder and open the yuzu.exe.

 yuzu will open and show this screen
 ![JustARandomString1](https://raw.githubusercontent.com/SkyeX9/Guide-To-Switch-Emulation/main/Yuzu_Images/yuzu_BDZoemVbLl.png)
 Dont worry about the error, just click okay, then on the top left of the app, click Emulation -> Configure -> System -> Profile
 Then press on Add and make a new profile, do what you want with the profile picture and the default Yuzu account it comes with. 
 I personally delete the yuzu user. 

  ## Files
 Inside of yuzu click File -> Open yuzu folder.
 This will open the yuzu configuration folder inside of explorer.

 Create a folder called "keys" and copy the prod.key you download from [here](https://github.com/emuworld/aio) and paste it in the folder.

Next, download and install Microsoft Visual C++ 2019 from [here](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you dont have it already installed.

  ## Settings
 For settings open yuzu up Emulation -> Configure -> Graphics, Select OpenGL and set it to Vulkan or OpenGL. (Vulkan seems to be a bit bad atm)
 Then go to Controls and setup any controller/keyboard layout you want for any of the 8 players. keep in mind, you need to press the excact buttons on your controller 
(if you have a controller/keyboard, keep it as a Pro Controller, if you use joycons, set them up as left/right joycons!)
 ![JustARandomString2](https://raw.githubusercontent.com/SkyeX9/Guide-To-Switch-Emulation/main/Yuzu_Images/yuzu_YhMWm8EfnI.png)
 After you're done press Okay and continue to the next step.

  ## Games
 Download any ROM you want from any ROM Website you like (I suggest going [here](https://nxbrew.com/)), or if your arent a Pirate, dump the gamecart from your Switch.
 After you got your File (can be .xci or .nsp) create a folder somewhere on your PC (preferably in the same location you extracted Yuzu to) and name it "games", then proceed to  make another folder, give it the games name. Copy/Extract/Move your ROM file to that folder. After that double-click into yuzu and select the "games" folder.

Once you have done this step, right click the new folder the shows up in yuzu, and select the "Scan Subfolders" option. 
 ![JustARandomString3](https://raw.githubusercontent.com/SkyeX9/Guide-To-Switch-Emulation/main/Yuzu_Images/yuzu_cWZ4UfNp2A.png)
 Now the game should be in the list.

 ## GameCart-Dumping

  For any of you with a modded switch, and want to dump your own game carts, instead of being a pirate, I found a very good guide that can be found [here](https://wiki.no-intro.org/index.php?title=Nintendo_Switch_Dumping_Guide)
  When you get the XCI on your computer, just do the same as in the [games](#games) section

 # Additional
  ## Compatibility

  For a Compatibility List of Games working look [here](https://yuzu-emu.org/game/)

  ## GameUpdates

 Download the update of your game or DLCs, usually as a .nsp.
 Put it in the folder of the game, then open yuzu. Do exactly as I do in the GIF below
 ![JustARandomString4Gif](https://raw.githubusercontent.com/SkyeX9/Guide-To-Switch-Emulation/main/Yuzu_Images/B7j0pc9ICO.gif)

  ## BCATS

  Whats a BCAT?
  A BCAT is the way of Nintendo sending you Ingame Gifts.
  On an Emulator this, obv, doesnt works as on a Switch, so Yuzu has its own way of giving you these.
  To Enable this go in the menu and choose Boxcat. ![here](https://raw.githubusercontent.com/SkyeX9/Guide-To-Switch-Emulation/main/Yuzu_Images/yuzu_bN24pp6u7N.png)
 <p> A list of all the stuff you can get can be found [here](https://yuzu-emu.org/help/feature/boxcat/)


  ## Addons

 He is a simple way of installing addons/mods
 It's pretty simple, we're gonna take the mod for pokemon mystery dungeon from [here](https://gbatemp.net/threads/pokemon-mystery-dungeon-dx-60-fps-mod.559469/). 
 When you download the zip file you will have a folder called "exefs_patches".
 Go inside that folder and in the other folder in there until you are at this file with an .IPS

 ![JustARandomString5](https://raw.githubusercontent.com/SkyeX9/Guide-To-Switch-Emulation/main/Yuzu_Images/explorer_0sHfAXoMTu.png)
  <p> Then move that IPS file into exefs_patches and delete the now empty folder.
 Then rename exefs_patches into exefs.
 Now open yuzu and rightclick your game -> Open Mod Directory.
 Create a new folder with any name you want and move the exefs folder into that, then restart yuzu and you're done.
 You now see your mod at compatibility.
 - Additional Notes:
 If you have any other names for the folder, do NOT rename it to exefs.
 Instead rename them to romfs or romfs_ext.

 You can completly skip these steps if you use mods from [here](https://github.com/yuzu-emu/yuzu/wiki/Switch-Mods) or [here](https://yuzu-emu.org/game/)

  # Goodbye

 Thank you for reading this, I hope it helped you with your start into Switch Emulation.
 If I forgot something just create a Pull Request with the stuff added and I will review it ASAP.
