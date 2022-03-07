# ECS2Excel

(Please see copyright section below)


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


---------------------------

Copyright (c) 2022 Dell Technologies

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE



