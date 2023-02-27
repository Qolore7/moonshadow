<a href="https://www.nexusmods.com/skyrimspecialedition/mods/85896"><img src="https://staticdelivery.nexusmods.com/mods/1704/images/85896/85896-1677468574-1704277277.png" target="_blank"></a>

---

<p align="center">
  <a href="https://www.nexusmods.com/skyrimspecialedition/mods/85896">Nexus Page</a> ·
  <a href="README.md">Installation</a> ·
  <a href="GAMEPLAY.md">Gameplay Guide</a> ·
  <a href="CHANGELOG.md">Changelog</a> ·
</p>

---

# Installation

- [Introduction](#introduction)
  - [List Contents](#list-contents)
  - [Minimum Specs](#minimum-specs)
  - [Community](#community)
- [Installation](#installation)
  - [Pre-Install](#pre-install)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Library](#steam-library)
    - [Set the Game language to English](#set-the-game-language-to-english)
    - [Clean Skyrim](#clean-skyrim)
    - [Start Skyrim](#start-skyrim)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
    - [Downloading and Installing](#downloading-and-installing)
      - [Problems with Wabbajack](#problems-with-wabbajack)
    - [Pagefile in prevention of memory crashes](#pagefile-in-prevention-of-memory-crashes)
  - [Skyrim GOG](#skyrim-gog)
- [Updating](#updating)
- [Startup](#startup)
- [Issues](#issues)

# Introduction

Moonshadow is an extremely lightweight and performance friendly modlist focused on roleplaying and creating a harsh fantasy world de-centralized from the player that incentivizes preperation and strategy. Moonshadow is built around "double-edged" gameplay, meaning that racial abilities, standing stones, and even perks come with both positives and negatives. Building a character is no longer about simply filling out a perk tree and getting numbers as high as possible. Intense thought and strategy need to go into building a character and leveling. Moonshadow prioritizes simple and intuitive mechanics, meaning you shouldn't need to delve into a wiki just to figure out how to complete a simple task. You can read more on the [Gameplay Changes](GAMEPLAY.md) page.

## List Contents

You can browse the full list contents [here](https://loadorderlibrary.com/lists/moonshadow-wip) if you want to know exactly what you're getting.

You can find a summary of all changes on the [Gameplay Changes](GAMEPLAY.md) page.

## Minimum Specs
Moonshadow was built with prioritizing performance over graphical fidelity in mind. In my opinion, it is easier for users with high-end PCs to add to the list than it is for low-end users to remove from the list. That being said, there are plenty of graphics mods used to greatly enhance the game's visuals without tanking performance. Moonshadow is built for a steady 60 FPS on mid-tier PCs and even potentially 144 FPS on high-end PCs. I get a mostly steady 60 FPS with my Ryzen 7 1700, RX 570, and 16gb of RAM. 

## Community

Support is offered in the [Viva New Vegas](https://discord.gg/DhX5S27) Discord server and in the [Issues](https://github.com/Qolore7/moonshadow/issues) section of the Moonshadow GitHub. If you have any questions following the add-on's instructions or if you find a typo or any other mistake in the documentation, feel free to report in The Lost Outpost Discord server's support channel.

## Skyrim: Anniversary Edition (AE)

This list is uses the free Anniversary upgrade for Skyrim Special Edition, a.k.a version 1.6.640.0. The paid upgrade is not required and will be ignored if you have it installed. 

# Installation

Installation is handled through [Wabbajack](https://www.wabbajack.org/#/) with a one-click install of the modlist. There are some pre-installation steps which must be followed for first time users so please pay attention to those.

## Pre-Install

These steps are only needed if you install the Modlist for the first time. If you are updating the Modlist, jump straight to [Updating](#updating).

### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. This package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

### Steam Library

If you have your Steam library in Program Files, read [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to put it somewhere else.
I will not provide support to people with Skyrim in their Program Files folder.
Locations like Documents, Downloads, Desktop, or OneDrive are NOT fine. The best location would be `C:\SteamLibrary` if you have a single drive, or whichever Drive Letter you have on your main Games drive. Such a location is also called the "root of the drive."

### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it.

[THIS](https://imgur.com/a/1dySo8q) is approximately what a clean Skyrim install should look like after shredding or cleaning it manually.

### Start Skyrim
Start the game and exit once you're in the main menu. This will ensure any settings files needed by Wabbajack are created in the Skyrim directory.

## Using Wabbajack

### Preparations

Download the release to a _working folder_. This folder **must not** be in a _common folder_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in the _working folder_.

### Downloading and Installing

The download and installation process can take a little while (an hour or more) depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Create a folder for the List at the root of your drive (like the Wabbajack folder) called "Moonshadow"
2. Go back to your drive, and create a new folder, called "Wabbajack Downloads Folder". This specific folder can be on a different drive if you wish
3. Download the latest release of `Moonshadow` from the [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/85896) page
4. Select the created folder in step 1 as your installation folder
5. Select the created folder in step 2 as your downloads folder
6. Click the Go/Begin button and wait for Wabbajack to finish

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

Seriously, simply retrying the Wabbajack download fixes most problems.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until I update the Modlist.

Some files are known to be problematic, it is likely those are the ones that failed. You can download them manually from their source and place the archives **AS IS** in the downloads folder.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Pagefile in prevention of memory crashes

Bigger Skyrim modlists need a lot of memory, and when there is not enough available it may fail allocating more. To fix this, you'll want to have a bigger [page file](https://github.com/Lost-Outpost/dragonborn/blob/main/PAGEFILE.md)"

## Skyrim GOG

This modlist can be played on the GOG version of Skyrim. You will need to do a couple of extra steps which are listed [here](GOG.md)

# Updating

If this Modlist receives an update, please check the [changelog](CHANGELOG.md) before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your saves will be kept, but please check each update changelog to see if the update is save compatible. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

# Startup

Open the installation folder and double click on the program called `ModOrganizer.exe`.

Make sure the dropdown box on the right is set to `Moonshadow` and press the Run button.

# Issues

SUPPORT FOR MODIFIED LISTS WILL NOT BE GIVEN!

If you find an issue, please provide details in the [Moonshadow Github](https://github.com/Qolore7/moonshadow/issues) or in the [Viva New Vegas](https://discord.gg/DhX5S27) Discord server. Please provide as much info as you can.

Thanks to [Guitarninja2](https://github.com/Lost-Outpost/dragonborn/commits?author=Guitarninja2) for the read-me format taken from their wonderful [Dragonborn](https://github.com/Lost-Outpost/dragonborn) modlist.
