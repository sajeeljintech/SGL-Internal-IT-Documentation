---
description: This area is for referencing IT and TECH issues for customers for reference
---

# Remote Desktop & VPN Trouble Shooting

**VPN -** The VPN connection is established by user for access to their remote desktop session. VPN must be installed, logged into, and turned on for any RDP conenction to be established to our in house hosted RDP server. (ProxMox)&#x20;

**Remote Desktop -** To sign into the session where they can reach the client, users my establish their remote desktop connection. This is assigned to them when their users are added by SGL support staff on the RDS server in the active directory.&#x20;

**Client Connection -** This is the log in connection to 4D to the client database which is the user's SGL Log in now that everoyne is linked.&#x20;

**Checking Customer VPN Status:**&#x20;

If a client is experiencing issues with their VPN Connection we can check status here:  [http://vpn.showgroundsonline.com/admin](http://vpn.showgroundsonline.com/admin)&#x20;

**Date:** 05/15/2024

**Customer:** Sonoma&#x20;

**Issue:** Lyn Nelson reported that her VPN being on creating a very laggy experience. When she has the VPN turned on her machine and network are all VERY slow but when VPN is off everything works as it should, however she then can no longer reach the server or database that she needs for the show.&#x20;

**Fix:**

**Future Diagnostic Questions/References:**&#x20;

* Run a speed test and get us the screenshot of the reuslts&#x20;
* Are you ON SITE - Lyn ended up NOT being on property

**Date:** 05/08/2024

**Customer:** Blenheim&#x20;

**Issue:** Retha (only her, not multple users) kept being booted out of her RDP session every so often. We enlisted the assistnace from Josh & Desmond & Wes to diagnose and correect the issue&#x20;

**Fix:** Change of the subnet network (IP addaresses)

**Future Diagnostic Questions/References:**&#x20;

* What is your IP Address?
* What type of machine are you on?&#x20;
* When did this start happening/ when is the last time you got booted out?&#x20;
* Is this just your machine or multiple users?



**Date:** 8/4/24

**Customer:** Menlo

**Issue:** Alice could not get her OpenVPN application to open on her Windows computer. She tried restarting her computer multiple times. When she would click to open the application, her computer would do nothing. Her user did not show as being connected on the OpenVPN admin site. Her task manager did not show the OpenVPN as being open. This was on a windows computer.&#x20;

**Fix:** After some research, it appears that there are two options for fixing.&#x20;

1. Delete Temporary Files in Windows
   1. Press the Windows icon button + R together to open the 'Run' dialog.&#x20;
   2. Type %temp% and press ENTER. This opens the 'Temporary Files' folder.&#x20;
   3. Select all files by pressing Ctrl + A.&#x20;
   4. Press DELETE and confirm by clicking Yes in User Account Control prompt.&#x20;
2. Uninstall the Application
   1. Uninstall the application on the device.&#x20;
   2. Reinstall the program.&#x20;

The first fix worked for her computer.&#x20;

