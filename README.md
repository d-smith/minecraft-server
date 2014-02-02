Script (config.sh) to install Java and download the minecraft server jar. After config.sh is run, the server can be started via the run_mc_server.sh script.

The best way to run the server is to use screen. Start screen, run the command, then detach (ctl-a d). You can then log out and the server continues to run in the background. Later, to reattach to the app (to issue commands on the command line for instance) login then do a screen -r.

Note this is for Ubuntu Linux version 12.x running on AWS EC2 - remember to allow inbound traffic on port 25565 (or whatever port the minecraft server is listening on).
