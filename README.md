# Project Aden

### Important: Before commiting/after pulling
RPG Maker VX Ace uses .rvdata2 files that aren't easy to version control. In order to achieve it, we use [rvpacker](http://github.com/aketerson/rvpacker) to unpack them to a text file before commiting and pack them back to .rvdata2 after pulling/cloning.

##### Workflow
* Checkout projectaden from here
* Run 'rvpacker --action pack --project <path-to-project> --project-type ace' on the project to repack it for the RPG Maker tool
* Load up RPG Maker and do whatever you're going to do; save the project
* Run 'rvpacker --action pack --project <path-to-project> --project-type ace' on the project
* Commit everything to version control (.gitignore is set to ignore the Data directory since you don't need it)
