# Check_Disk_Space
A Powershell script that returns diskdrives and their diskspace utilization to the user.

The BREAKDOWN:

############ WriteToLog.ps1 ###############
WriteToLog is a function that accepts a user, a script name, and a log Name. 
It gets the current date, and then updates the log file specified in the Out-file command.

This file is used for logging purposes only.

############ GUI_Check_Disk_Space.ps1 ###############
This file acts a graphic user interface for a admin that wishes to use the CheckDiskSpace.ps1 script without using the command line.

It imports the WriteToLog and CheckDiskSpace files.

It has a button to check for server drives and their utilization. 
Please alter this script to your needs as my needs may vary from yours.

You can read the rest of the details in the script itself. I fully commented it.

############ CheckDiskSpace.ps1 ###############
This file has a function that accepts a server and returns all the drives as well as their utilization.
To see the full details check out the script. I fully commented it.

You can use anywhere from one to all three scripts depending on your needs.
