# CodeShare.in

This repository contains source code for https://codeshare.in

To share a file, download the CodeShare.in command line client
from https://github.com/baijum/codeshare/releases . Alternately,
if you have Go compiler installed, you can get it like this:

	go get github.com/baijum/codeshare/cmd/cs

Sharing file is as simple runnig the client with file path as argument.

	cs /path/to/file.txt

Once the file is uploaded to the server, a URL to access the file
online will be printed.

Note: The file will be accessible for 7 days from the server.
