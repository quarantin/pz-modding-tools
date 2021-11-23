# Save / Load

## Description
This is a set of script to be able to backup and restore your Project Zomboid save files.

## Install
- Run the following commands:
		MODTOOLS=/path/to/this/repo
		cd ${MODTOOLS}/tools/saveload/
		sudo cp -a zconf zload zsave /usr/local/bin

## Usage
- Perform a backup of your saved files:
		zsave
- Restore a backup of your saved files:
		zload
