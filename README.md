## Description:

**Sublime LC2200** is a *Sublime Text 2* syntax package for LC2200 assembly code.

## Includes:
- commenting with "!" using the comment keyboard shortcut
- 2 different highlighting schemes
	1. **inst pseudoinst**: Operations divided only into 2 catagories 
		- instructions
		- pseudo-instructions
	2. **multi-catagory**: operations divided into multiple catagories
		- **arithmetic**: add, addi, nand
		- **controls**: beq, jalr, halt
		- **loading/saving**: lw, sw, la
		- **misc**: noop, .word

## Usage:

Install (Linux):
  
    cd .config/sublime-text-2/Packages
    git clone git://github.com/wufufufu/Sublime-LC2200.git

## Edit:

Edit .tmLanguage files  manually

**or**

Edit .JSON-tmLanguage language files and generate .tmLanguage files using [AAAPackageDev](https://bitbucket.org/guillermooo/aaapackagedev).

**Generating files from JSON file:**

	1. Install AAAPackageDev
	2. Open JSON file with Sublime Text 2
	3. build JSON file with ctrl-b
	4. choose "Convert To: Property List"