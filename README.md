# Developing Your Minecraft Texture Pack

So you've decided you want to make your own texture pack in Minecraft, but where do you begin? It's actually quite simple, and hopefully by the end of this guide, you'll feel confident in creating your own texture packs.

## Requirments 
  * [Minecraft Java edition](https://www.minecraft.net/en-us/store/minecraft-java-edition)
    * ( Do not use a cracked version Minecraft. )
  * [WinRAR](https://www.win-rar.com/start.html?&L=0)
    * WinRAR is a file archiver application that we will use to extract the texture pack assets from the game's `{version}.jar` directory.
  * [Gimp](https://www.gimp.org/downloads/)
    * Gimp is a free [raster graphics editor](https://en.wikipedia.org/wiki/Raster_graphics_editor) that we will use to alter existing textures as well as create our own.

## Setup

To begin constructing our texture pack, we must first create a new folder that will store all of our information and data for our pack to use in Minecraft. For the sake of convenience and keeping track of your pack, I recommend making a folder on your computer's desktop for the time being. Once finished, this is where you may inject your first dash of individuality into your pack. Color and format codes can also be used to create a more uniform theme with your pack. We can proceed to our primary setup once you've decided on a name and design for your pack that you like.

## Assets

Let's begin by gathering the basic components that we'll need to make the pack. If you're using Windows, you can easily obtain the game assets for your preferred game version by navigating through the game files and into the `versions` folder. To get here, use `Win + R` to enter `Run.` This will prompt you with a tool named run that you can use to hastily navigate into specific directories. Once you're inside of here, type in `%appdata%` and hit enter. You must now browse to the `.minecraft` directory, which should be at or at the very top of your roaming folder for most users. Once you've found this folder, open it and browse to the `versions` subfolder. When you open this, you will see all of the mentioned game versions, but if you don't see your desired game version, start and run a new Minecraft world with your chosen version, and the game assets will appear in the versions folder. When you have obtained your selected game version, you may now access the folder with the title of your game version. Within this folder, you will find two files, one labeled `version.jar` and the other `version.json`. You wish to use WinRar to open the `version.jar` file. If the `.jar` file is not already formatted as a WinRar file, you can open it using 'open with' or alter the file's properties to WinRAR. Once opened, you may extract the 'assets' folder to your desktop, and you will now have the proper basic setup for your pack. I recommend making a copy of this assets folder so you don't have to repeat the process every time you make a texture pack. However, if you want to make a texture pack for a different game version, you cannot simply rename the pack to the appropriate game version. You'll need to go back to your versions folder and extract the assets for the new game version you want.

## MCMeta

The file `pack.mcmeta` is another important setup function that we will need to implement into our texture pack.

### Guide Info: Last Updated by [Jack Levreau](https://www.github.com/kyrncion) - 1/13/2021
