# Connecting an AP to WLC

# Step 1: Preparation
- 1 switch
- 1 AP
- 1 console cable
- 2 RJ45 (one for Switch - AP, one for AP - computer)
- a laptop
- WLC.

# Step 2: Setup
- Turn off Wifi Adapter
- Set up an IP address in the same network with the default IP address of an AP
- Go to the AP's GUI
- Use the default password and username of the AP (Check its back to see the info) to log in the AP's GUI and change a new password for it!

# Step 3: Configuration
- Go to "Management" -> Enable "Set Controller Address"
- Fill in the IP address of WLC as "Primary Controller Addr"
- Fill in an IP address of the "Secondary Controller Addr" if having one. If not, leave it empty
- Save the configuration by pressing "Update Settings".

# Step 4: Reboot + Connect the AP to the same network of WLC
- Reboot to take effect
- Connect the AP to the same network of WLC by plugging an ethernet cable of the network.

# Step 5: Check on WLC
- Check if the AP appears in Network - APs section
- Refresh to see the AP starting upgrading its firmwares automatically.

You're done! Congrats!
