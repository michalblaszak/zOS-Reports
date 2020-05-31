This is a set of REXX scripts to diagnose z/OS performance.
The scripts are a final challenge for Mastering Mainframe course.

----------------------------------------------------------------------------
get - an entry point to all other scripts. Displays the following option menu:
----------------------------------------------------------------------------

   System Information Utility

   Information requested:
   1. Report specific message identifier found in SYSLOG
   2. Report from System Information, SYS
   3. Report string found in SYSLOG
   4. Report TSO logons
   5. Report specific ID successful TSO logon
   6. Report Active Jobs
   7. Report ............................

   Enter report number

----------------------------------------------------------------------------
1. Report specific message identifier found in SYSLOG
Script: msgid
Example report: msgid.txt
----------------------------------------------------------------------------

2. Report from System Information, SYS
Script: sys
Example report: sys.txt
----------------------------------------------------------------------------

3. Report string found in SYSLOG
Script: strng
Example report: strng.txt

----------------------------------------------------------------------------
4. Report TSO logons
Script: logons 'ALL'
Example report: logons.txt

----------------------------------------------------------------------------
5. Report specific ID successful TSO logon
Script: logonid -> logons user_id
Example report: logonid.txt

----------------------------------------------------------------------------
6. Report Active Jobs
Script: da
Example report: da.txt

----------------------------------------------------------------------------
7. Report ............................
Not implemented 
----------------------------------------------------------------------------
