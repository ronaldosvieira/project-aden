# Project Aden

### Description
An RPG made by a bunch of bored nerds based on a medieval fantasy story that involves a lot of magic, blood, bad jokes and some Game of Thrones like dragons. It uses RPG Maker VX Ace engine and D&D stuff.

### How to Play
The game is in very very very early alpha stage (i.e. version 0.0000001). But if you're too hyped and can't wait to play, you can make a clone of this repository, do the 'Important: Before commiting/after pulling' step and double-click `Game.exe`.

### How to Contribute
* Install [RPG Maker VX Ace](http://www.rpgmakerweb.com/products/programs/rpg-maker-vx-ace).
* Clone this repository into a folder of your choice.
* Read the 'Important: Before commiting/after pulling' section down there.
* Open `Game.rvproj2` in RPG Maker VX Ace.
* Do ya thang.

RPG Maker isn't a seven-headed monster (though I can't say the same for the monsters in the game MWA HA HA!) but you may want to read some tutorials on the internetz for the more complicated features.

### Important: Before commiting/after pulling
RPG Maker VX Ace uses .rvdata2 files that aren't easy to version control. In order to achieve it, we use [rvpacker](http://github.com/akesterson/rvpacker) to unpack them to a text file before commiting and pack them back to .rvdata2 after pulling/cloning.

##### Workflow
* Checkout projectaden from here.
* Run `pack.bat` in the `projectaden/rvpacker` folder to repack it for the RPG Maker tool.
* Load up RPG Maker and do whatever you're going to do; save the project.
* Run `unpack.bat` in the `projectaden/rvpacker` folder.
* Commit everything to version control (.gitignore is set to ignore the Data directory since you don't need it).

##### Notes
* You may want to read the 'Installation' section on [rvpacker's page](http://github.com/akesterson/rvpacker).
* By the moment I'm writing this, you still need to install Ruby and probably the Ruby DevKit to contribute (I know, sorry! At least the .bat files saved you from writing a pretty long command every time you contribute).
