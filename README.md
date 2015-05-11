# Project Aden

### Description
An RPG made by a bunch of bored nerds based on a medieval fantasy story that involves a lot of magic, blood, bad jokes and some Game of Thrones like dragons. It uses RPG Maker VX Ace engine and D&D stuff.

### Important: Before commiting/after pulling
RPG Maker VX Ace uses .rvdata2 files that aren't easy to version control. In order to achieve it, we use [rvpacker](http://github.com/akesterson/rvpacker) to unpack them to a text file before commiting and pack them back to .rvdata2 after pulling/cloning.

##### Workflow
* Checkout projectaden from here
* Run `pack.bat` in the `projectaden/rvpacker` folder to repack it for the RPG Maker tool
* Load up RPG Maker and do whatever you're going to do; save the project
* Run `unpack.bat` in the `projectaden/rvpacker` folder
* Commit everything to version control (.gitignore is set to ignore the Data directory since you don't need it)
