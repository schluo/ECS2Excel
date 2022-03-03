# ECS2Excel

Helps archiving historical capacity values due to the fact that ECS is only able to store the values for 2 month.

Tool should be started by cron or Windows Task Scheduler. The Excel Sheet will get one more column/row per call.

Windows EXE Version avaible in /Dist

'================================================================

Dell EMC ECS Capacity Report as MS Excel Sheet V 1.2.0

'================================================================

usage: ECSCapa2XLS.py [-h] -H HOSTNAME -u USERNAME -p PASSWORD -f FILENAME [-v] [-b]



  -h, --help            show this help message and exit
  
  -H HOSTNAME, --hostname HOSTNAME
                          hostname or IP address and Port
                          
  -u USERNAME, --username USERNAME
                        username
                        
  -p PASSWORD, --password PASSWORD
                        user password
                        
  -f FILENAME, --filename FILENAME
                        Excel Sheet filename
                        
  -v, --verbose         verbose logging
  
  -b, --bucket          reporting based on buckets
  



