# Aruba Switch

## Step 1: Download a TFTP server

Free version: Tftpd64, Solarwinds

## Step 2:

Set up your file path, security, and copy and paste your nessary file in the folder.

## Step 3:

Power on your switch

Check you switch version and flash 

show version 

show flash

## Step 4:

Use your switch to ping tfpt server. Ensure it ping succesfully! If not, turn off your firewall on the device having service.


## Step 5:

ipconfig /all to find out your device IP where having your TFTP server! 

In this case Your Device's IP = TFTP server

Copy that IP!

## Step 6:

en mode -> config mode -> copy tftp flash TFTP's server address File's name primary/secondary

## Step 7: 

Reboot!

## Step 8:

write memory 

save the config!!!

##
