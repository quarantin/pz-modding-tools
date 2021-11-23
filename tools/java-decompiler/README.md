# Java Decompiler

## Description
This is a simple script to decompile Java code.
It's using the java-decompiler plugin from IntelliJ to do the work.

## Install
- Download IntelliJ and extract the archive.
- Then run the following commands:
		MODTOOLS=/path/to/this/repo
		INTELLIJ=/path/to/IntelliJ
		sudo mkdir /opt/java-decompiler
		sudo cp ${INTELLIJ}/java-decompiler/lib/java-decompiler.jar /opt/java-decompiler
		sudo cp -a ${MODTOOLS}/tools/java-decompiler/java-decompiler /usr/local/bin/

## Usage
In this case, INPUT points to the location of the class files to decompile.
OUTPUT points to where you want to write the decompiled files:
	INPUT=/path/to/source
	OUTPUT=/path/to/destination
	java-decompiler ${INPUT} ${OUTPUT}
