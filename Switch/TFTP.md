Aruba Switch

Step 1: Download a TFTP server

Free version: Tftpd64, Solarwinds

Step 2:

Set up your file path, security, and copy and paste your nessary file in the folder.

Step 3:

Power on your switch

Check you switch version and flash 

show version 

show flash

Step 3:

Use your switch to ping tfpt server. Ensure it ping succesfully! If not, turn off your firewall on the device having service.


Step 4:

ipconfig /all to find out your device IP where having your TFTP server! 

In this case Your Device's IP = TFTP server

Copy that IP!

Step 5:

en mode -> config mode -> copy tftp flash TFTP's server address File's name primary/secondary

Step 6: 

Reboot!


