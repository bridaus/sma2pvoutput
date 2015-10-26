This is a simple Powershell script to take the data from one or more SMA inverters and upload it to pvoutput.org. It requires the Sunny Explorer software from SMA to be installed on the Windows device on which the script is run in order to create the data exports.

The script can either take existing exports of status information for the specified date, or invoke Sunny Explorer to create an updated export. The contents of the export are then uploaded to pvoutput.org either individually or in batches.

It is designed to be run as a periodic scheduled task to perform status updates during daylight hours. The option then exists to schedule an end-of-day batch update of all the day's data to catch any statuses that may have been missed.

Click on the Downloads link on the left to get the script. Help on using the script is available from the Wiki link above.

Best of luck.

Neil

The legal stuff:

The script is provided 'as is' without any warranty of any kind. SMA and Sunny Explorer are registered trademarks of SMA Solar Technologies AG.