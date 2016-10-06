ChangeDataRetention script - repeated in Ch 04 and 09
==========================================================================
This script will change the default retention period for the reporting 
database. It should be run from SQL Query Analyzer targeted at the
SystemCenterReporting database.



GroomDays script - repeated in Ch 04 and 09
==========================================================================
This script will show you what the current setting for retention is in
the reporting database. It should be run from SQL Query Analyzer targeted 
at the SystemCenterReporting database.



13-1 script
==========================================================================
This script is used to check the DNS information for a machine. It can be
imported into MOM and launched from an event rule.



13-4 script
==========================================================================
This script is used to stop and start a Windows service and can be 
imported into MOM and launched from an event rule.



Checkdataforgrooming script
==========================================================================
This script is used to check data awaiting grooming to the
SystemCenterReporting database. It should be run from SQL Query Analyzer 
targeted at the OnePoint database.



Reportingcreationquery script
==========================================================================
This script is used in Visual Studio to obtain data to create the custom
report documented in Chapter 08


AddTable script
==========================================================================
This script is an example script to create a table in the user created
database used in Chapter 08


AddDatatoTable script
==========================================================================
This script is an example script to add data to a table in the user created
database used in Chapter 08 



FileCounter script
==========================================================================
This script is used to count the number of files in a folder and generate
a MOM event if the number counted is higher than the threshold. It should be
imported into MOM as a script and launched from an event rule.



Ping script
==========================================================================
This script pings devices according to the parameters set in MOM (under the
parameters tab in scripts) and generates a MOM event when one of the devices
does not respond. It should be imported into MOM as a script. You should
create a parameter on the parameters tab called IPAddress. Create an event rule
to launch the script. Create a single MOM event rule for each device to monitor
and change the script parameter in each rule to reflect the device you are pinging.
A MOM event will be generated for each device that does not respond to ping and
a success event will be generated every time a ping is successful.