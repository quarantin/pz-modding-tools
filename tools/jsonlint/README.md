# JSON Lint

## Description
This is a simple script to check for syntax error in JSON files.
It's using the Python module json.tool to do the work.

## Install
- Install any variant of Python
- The run the following commands:
		MODTOOLS=/path/to/this/repo
		sudo cp -a ${MODTOOLS}/tools/jsonlint/jsonlint /usr/local/bin

## Usage
Simply provide the list of JSON files to check for syntax errors:
	jsonlint config.1.json config.2.json config.3.json
