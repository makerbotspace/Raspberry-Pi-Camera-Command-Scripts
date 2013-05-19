Raspberry-Pi-Camera-Command-Scripts
===================================

Coomands for Raspberry Pi Cammera

This is a set of commands as executable files I put on my desktop.  You can run them by double clicking them and clicking the execute button.  They are Leafpad files with permissions set to Execute.  It is a quick way to test the camera.  


These commands all run form \home\pi\

All of the software used is part of the current build of wheezy for the camera 


Take a Still Picture named temppic.jpg

raspistill -o \home\pi\temppic.jpg 


Show the temppic.jpg file

gpicview \home\pi\temppic.jpg


Take a 22 second Video called tempted.h264

raspivid -hf -t 22000 -o \home\pi\tempvid.h264 


Play the tempted.h264 file

omxplayer \home\pi\tempvid.h264 


I installed vsftpd to move files to my other desktop 

sudo apt-get install vsftpd

Here is a link to how to install and configure it.

http://www.instructables.com/id/Raspberry-Pi-Web-Server/step9/Install-an-FTP-server/
