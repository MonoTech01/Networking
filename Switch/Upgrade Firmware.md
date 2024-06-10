1. Connect your switch with your computer by using a console cable. 
2. Search for "Device Manager" in your computer and check "Ports (COM & LP)" section to see what COM is.
3. Open Putty and fill in info of "Basic options for your Putty" section:
   
   Choose "Serial" as a connection type.
   
   Serial line = Com[number]
   
   Speed = [Speed number]
   
   Then click "Open"
   
5. In CLI, set up int VLAN management and its ip address. Remember to associate a port to a VLAN by untagging that port as known as that interface
   untagged port = access port = is associated with only one VLAN => not a trunk port
6. Use the management IP address that you just set up to access the switch's GUI. Copy and paste the IP to the web browser
7. When the GUI opens, choose System -> Firmware. Then, you will see that you can upload your new firmware there.
8. Find your correct software of your switch. You can find it in the offical website of your switch's brand. Download the correct one.
9. Upload your firmware in the website. Then check "show flash" to see it in the switch. Remember to upgrade your primary one before upgrade your second one aka a backup one. You have to that to make sure that the new firmware works. If the new firmware does not work, you can use the backup to make it function properly again.
10. Upgrade your firmware
    
   In CLI, reboot or reload in config mode

   Then confirm "yes" that you want an upgrade.

   Wait............until it is done!

   Then check "show flash" to see the new version there, but you will also see the new version when it finishes booting up!

11. Now, you can do the same thing with your backup firmware!
12. After all, you should save the config

Nice! Congrats that you successfully upgrade your firmware (both the primary and second ones)!
