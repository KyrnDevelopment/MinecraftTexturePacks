# Creating A Minecraft Texture Pack

So you finally decided you would like to create your very own texture pack in Minecraft, but where to start? Well, it's quite simple and hopefully, by the end of this guide, you will feel comfortable making your own texture packs.

## Requirments 
  * [Minecraft Java edition](https://www.minecraft.net/en-us/store/minecraft-java-edition)
    * ( Don't use cracked Minecraft )
  * [WinRAR](https://www.win-rar.com/start.html?&L=0)
    * WinRAR is a file archiver utility that we will be using to extract the needed assets for our texture pack from the game's `{version}.jar` directory. 
  * [Gimp](https://www.gimp.org/downloads/)
    * Gimp is a [raster graphics editor](https://en.wikipedia.org/wiki/Raster_graphics_editor) that we will be using in order to edit pre-existing textures and to create our own.

## Setup

To start off creating our texture pack we need to make a new folder that will contain all of our information and data for our pack to implement into Minecraft. For simplicity, as well as simply keeping track of your pack, I recommend for now creating a folder on the desktop of your computer. Once completed, here is where you can implement your first splash of personality into your pack. You can use color and format codes as well to create a more consistent theme with your pack. Once you've settled on a name and design for your pack that you like we can move on to our primary setup.

## Assets

Let's start off with getting the base assets that we will need in order to create the pack. If you're on windows a simple way to grab the game assets for your desired game version is by going through the game files into the `versions` folder. To get here, navigate into `Run` with `⊞ Win + R`. This will prompt you with a tool named run that you can use to hastily navigate into specific directories. Once you're inside of here, type in `%appdata%` and hit enter. You will now have to navigate to the directory labeled `.minecraft`, which for most users, should be located near or at the very top of their roaming folder. Once you've located this folder, open it and navigate into the subdirectory called `versions`. When you open this you will be able to find all the listed game versions, but if you don't see your desired game version you can open and run a new Minecraft world with your desired version and the game assets will appear in the versions folder. Once you finally have your desired game version you can now open up the folder with your game version's title. Inside this folder, you will see two files, one being labeled `{version}.jar` and the other being `{version}.json`. You want to open up the `{version}.jar` file with WinRar. If the `.jar` file is not already formated into a WinRar file you can click `open with` or change the properties of the file into WinRAR. Once opened,  you can extract the folder named `assets` onto your desktop and now you will officially have the base setup for your pack. I recommend creating a copy of this assets folder so you do not have to redo that process every time you create a texture pack. However, if you wish to create a texture pack for a different game version you cannot simply rename the pack to your desired game version. You will need to go back to your versions folder and extract the assets for the new game version you want.

## MCMeta

Another crucial setup function that we will need to implement into our texture pack is the file called `pack.mcmeta`.
