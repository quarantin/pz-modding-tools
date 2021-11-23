# Lua Lint

## Description
This is a simple script to check for syntax errors in Lua files.
It's using luajit to do the work.

## Install
- Install luajit
		sudo apt install luajit
- Run the following commands:
		MODTOOLS=/path/to/this/repo
		sudo cp -a ${MODTOOLS}/tools/lualint/lualint /usr/local/bin

## Usage
- Check for syntax errors in all Lua files available in current directory and subfolders:
		lualint
- Check for syntax errors in a list of Lua files:
		lualint file1.lua file2.lua
