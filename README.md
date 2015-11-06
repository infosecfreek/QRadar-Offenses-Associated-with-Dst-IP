# QRadar-Offenses-Associated-with-Dst-IP

About:

This script presents you the list of offenses that are associated with the destination IP addresses. In this you will get the details (in tabular format) ,only if the Destination address is associated/involved with more that one Offenses. This detail you cannot get from the GUI easily at one place. In this you will get the offenes that got generated in last  days.

How to deploy:

Open the file, change the x.x.x.x mentioned in it with Qradar console IP address. Copy the DstIP_Offense.html to the /opt/qradar/webapps/console in your QRadar console using winscp. Now you can access this with following url: https://x.x.x.x/console/DstIP_Offense.html
