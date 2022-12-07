
# Backup Unraid Server offsite
In this article I want to explain you how I backup my Unraid Home Server to another Unraid server.
***
## My setup
I have two Unraid servers. 
One running at my home and one at another offsite location. The server running at my home is running some Docker Containers and it serves as my NAS. 
So it is important for me that all the configurations of my Docker Containers and the files from my NAS are backed up.

This server has a total capacity of 8TB. 2TB of space is occupied at the time of writing.

The second server is an old computer with some old hard drives in it. 
Sure it is not the best idea to run a server with old hard drives 24/7 but that is not my plan. 
I plan on turing on the server when it is time to backup the files and turn it off again when the backup is finished. 
So the drives do not need to spin all day and the server uses no energy while it is turned off. 
This is also important because I don't want my friends energy bill to spike up just because of my data.

The backup server has a capacity of 5TB at the time of writing. 
I plan on upgrade the hard drives in this server as soon as possible because the actual drives are already 2-5 years old. 
## The plan
