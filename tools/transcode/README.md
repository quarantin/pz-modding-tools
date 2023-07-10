# Transcode

## Description
A script to transcode Project Zomboid translation files to correct charset according to language.
It's using iconv to do it's work.

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
- Install iconv:
		sudo apt install
- Follow the instructions to install modtools.json
- Change directory to this repo:
		MODTOOLS=/path/to/this/repo
		cd ${MODTOOLS}
- Run the following command:
		sudo cp -a ${MODTOOLS}/tools/transcode/transcode /usr/local/bin

## Usage
- Usage:
		transcode <mod id>
- Example:
		transcode MyMod
