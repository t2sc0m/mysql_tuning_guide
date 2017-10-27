# Mysql Tuning Guide 
---
## Mysql Tuning Guide Script
![tescom](https://en.gravatar.com/userimage/96759029/aa4308f795041de37cc2fedf0d1071ca?size=128)
---

Based on the [MySQL performance tuning primer script](https://launchpad.net/mysql-tuning-primer) version 1.6-r1 released on 2011-08-06 by Matthew Montgomery and licenced under the GPLv2.

---
## Usage
```shell
$ ./tuning_guide.sh [all|prompt|mem|disk|innodb|misc]

```  
## Modes
```shell
all :    perform all checks (default)                          
prompt : prompt for login credintials and socket              
         and execution mode                                  
mem :    run checks for tunable options which               
         effect memory usage                               
disk :   run checks for options which effect              
         i/o performance or file handle limits           
innodb : run InnoDB checks /* to be improved */         
misc :   run checks for that don't categorise          
         well Slow Queries, Binary logs,              
         Used Connections and Worker Threads
```  
