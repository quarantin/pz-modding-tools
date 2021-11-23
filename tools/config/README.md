# Config

## Description
This is the JSON configuration for the following modding tools:
- publish
- transcode

These tools won't work if you don't edit and install this JSON file property.

## Install
- Change directory to modtools config:
		MODTOOLS=/path/to/this/repo
		cd ${MODTOOLS}/tools/config
- Copy modtools.json.example to modtools.json:
		cp -a modtools.json.example modtools.json
- Open modtools.json with your favorite text editor
- Edit modtools.json according to your mods.
- Run the following command:
		cp -a modtools.json /usr/local/bin
