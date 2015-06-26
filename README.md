ShellShock-CGI-Scan
===================

A script, in C, to check if CGI scripts are vulnerable to CVE-2014-6271 (The Bash Bug).

Options:

	-i (local ip-address)
	
	-p (port to listen)
	
	-l (site list)
	
	-t (connection timeout) (Default: 15s)

Example:
  $ ./Scanner -i 127.0.0.1 -p 31337 -l sites.txt -t 5

  Starting listen in localhost on port 31337, scan sites in file 'sites.txt', and set connection timeout to 5 seconds.

Preview:

![alt tag](https://dl.dropboxusercontent.com/u/53811115/mmxm.png)
