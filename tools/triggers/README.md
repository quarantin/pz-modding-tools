# Triggers

## Description
This is a script to search for triggered event in Project Zomboid source code.
It's using vim to inspect the files.

## Install
- Install vim:
		sudo apt install vim
- Run the following commands:
		MODTOOLS=/path/to/this/repo
		cd ${MODTOOLS}/tools/saveload/
		sudo cp -a ${MODTOOLS}/tools/triggers/triggers /usr/local/bin

## Usage
- Go to your Java source directory:
		JAVASOURCE=/path/to/zomboid/java/sources/
		cd ${JAVASOURCE}
- Run the command with the name of a Lua event as parameter:
		triggers OnPlayerUpdate
