# Publish

## Description
A script to export your git repository to Project Zomboid Workshop directory, ready for publishing to Steam Workshop.

## Install modtools.json
- Change directory to modtools config:
		MODTOOLS=/path/to/this/repo
		cd ${MODTOOLS}/tools/config
- Copy modtools.json.example to modtools.json:
		cp -a modtools.json.example modtools.json
- Open modtools.json with your favorite text editor
- Edit modtools.json according to your mods.
- Run the following commands:
		cp -a modtools.json /usr/local/bin

## Install
- sudo apt install dos2unix
- Follow the instructions to install modtools.json
- Change directory to this repo:
		MODTOOLS=/path/to/this/repo
		cd ${MODTOOLS}
- Run the following command:
		sudo cp -a ${MODTOOLS}/tools/publish/publish /usr/local/bin

## Usage
- Usage:
		publish <mod id> <version>
- Example:
		publish MyMod 1.2
