# TigerWoods08-Windows11
Instructions on how to play Tiger Woods 08 on Windows 11
Credit - https://www.reddit.com/r/EASportsPGATour/comments/11b4hwu/tiger_woods_pga_tour_2008_on_win11/

When you install the game make sure you install the adobe flash files if it asks you too. Don't install the online components.

# Widescreen Patch
Download and install UniWS (https://www.wsgf.org/article/universal-widescreen-uniws-patcher)

Run UniWS and select the game Tiger Woods 2004 (custom menu resolution). Direct the game installation directory to the bin directory of TW 08.

Enter your monitor resolutions height and width and click the Patch Button. 21:9 monitors the in-game bottom menus are cut off a bit, which you can see from my screenshot photo.

# DgVoodoo2
Download the latest version of DgVoodoo2 (http://dege.freeweb.hu/dgVoodoo2/dgVoodoo2/)

Open the zip file with 7zip or windows explorer.

Copy both dgVoodooCpl.exe and dgVoodoo.conf to the bin directory of TW 08

In dgVoodoo2 zip file open the MS directory and copy all .dll files from the x86 directory to TW 08 bin directory.

Run dgVoodoo2Cpl.exe

Make sure the config folder / running instance is directed to the bin directory of TW 08.

Under the General tab select the adapter to use. You can select your GPU or you can leave it with the default selection "All of them".

In the Miscellaneous category. Uncheck all options. Then select the DirectX tab.

In the DirectX tab. Make sure "Disable and passthru to real DirectX" is unchecked

In the Video Card category select dgVoodoo Virtual 3D Accelerated Card. Under VRAM select 128 MB or 256 MB. If you do not like the Voodoo watermark in the lower right corner of the screen uncheck dgVoodoo Watermark under Miscellaneous category.

# Bug Fix
There are files responsible for a memory leak. The file keeps getting bigger and bigger and eventually crashes the game. Unfortunately you’re going to have to do this with the pro golfers you want to use too!

After you have created your character. Play 1 hole on any course and exit the game. Next go to your documents directory and find Tiger Woods PGA Tour 08 directory. Go to \Career\Players\<your character name>\Confidence. Keep this window open because we're coming back to it. Delete all files in this directory. Run the game again. Play one hole and exit. Go back to the confidence directory, which should still be open and highlight all files with Ctrl+A. With second mouse button click on properties and set the file Attributes to Read Only.

And we're done! Enjoy the game!
