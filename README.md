# dbash

This is a little script for easy accessing your docker containers via shell.

## Install

	git clone https://github.com/Nasty/dbash.git /tmp/dbash
	cd /tmp/dbash
	cp dbash /usr/local/bin/dbash
	chmod +x /usr/local/bin/dbash


## How to use

For a list of your started containers. If there is only one docker container running, access instantly.

	dbash  

<br/>
To update this script (download from github)

	dbash update
	
<br/>
Accessing a specific container with the given id.

	dbash %CONTAINER ID%
	
