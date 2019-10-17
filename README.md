# Logic
Logic Code for Formal Analysis <br/>

Code for printing a truth table of an argument with any number of logic connectives or atomic sentences.

### Sample 1:  <br/>
Enter your logical statement e.g. (a and b) implies c / a ↔ b v c / a biconditional b 

 *Ensure there is space between the atomic sentences and the connectives!!* <br/>
> **not a and b or c implies (d)**

This is your input: not a and b or c implies (d)  <br/>
Your logical statement has 4 atomic sentences.  <br/>
+-------+-------+-------+-------+------------------------------+ <br/>
|   a   |   b   |   c   |   d   | not a and b or c implies (d) | <br/>
+-------+-------+-------+-------+------------------------------+ <br/>
|  True |  True |  True |  True |             True             | <br/>
|  True |  True |  True | False |             True             | <br/>
|  True |  True | False |  True |             True             | <br/>
|  True |  True | False | False |             True             | <br/>
|  True | False |  True |  True |             True             | <br/>
|  True | False |  True | False |             True             | <br/>
|  True | False | False |  True |             True             | <br/>
|  True | False | False | False |             True             | <br/>
| False |  True |  True |  True |            False             | <br/>
| False |  True |  True | False |            False             | <br/>
| False |  True | False |  True |            False             | <br/>
| False |  True | False | False |            False             | <br/>
| False | False |  True |  True |            False             | <br/>
| False | False |  True | False |            False             | <br/>
| False | False | False |  True |            False             | <br/>
| False | False | False | False |            False             | <br/>
+-------+-------+-------+-------+------------------------------+ <br/>

### Sample 2:  <br/>
![Output](https://lh3.googleusercontent.com/tcapaFrOSrgFri7xNs8Ot78yccU-9-f57DAxlXpxPAPSqDd0f02yPljaDbg9trHhJTvydAozs7SD8Q9_UYfVww1XHIaze-gBk75ZzjzTai91iW5PFsjhM3ldcxfJtb-HtjQWExGGjBIfDW9g9A7eQJUUWZhlBTan7DRrVOcpqvEKkDkeXzCyDVFqFt05-Z899BrHZpuHvMBBB-DOtnULUa5Q3Z3tpcsfSjBX27OeSSS-VY6vsoVq7nlDYgqmAkD2FF6dpPZTzbqbk00jm0GedeSLIwxku7J3nShS304fsRKiQtLG9ytm6erf9vtgySG2R1Ab0j2Q_mRkifGiFBFSA8SqDTrLXTMJkyzuwGuuJ0F330BivuZ_7j_T5hbeG1gJ5jDNaqjoUG9S1CDZdY-L8j9xKBPXKlTCzuziUrFtovcLVMbrona6s-asEBNCziMxVSvaKONuPSv0JJnZZKLIMJN3-1-QqK-qmx8rLaaBCvYgwzR8RlHEjBlF1SthV3V_VY_yP4qFIuzKAeu0FuGwE034oTS5wnTCigPwFOu927NvQRR_QxNwgyRumOey1eJoEOjGdCJRBiCZp8eElWk9_s2hYtuVZUpMh4eKQM0wWmae4rnmRgSDPfdAqK9Ty1ZAtIKgId2afVGM-F2hNKeOLS_uFS9yMgQMoEYof6HK6rdK0cZPt1WbSoE=w965-h453-no "Output")
[Link to Output](https://lh3.googleusercontent.com/tcapaFrOSrgFri7xNs8Ot78yccU-9-f57DAxlXpxPAPSqDd0f02yPljaDbg9trHhJTvydAozs7SD8Q9_UYfVww1XHIaze-gBk75ZzjzTai91iW5PFsjhM3ldcxfJtb-HtjQWExGGjBIfDW9g9A7eQJUUWZhlBTan7DRrVOcpqvEKkDkeXzCyDVFqFt05-Z899BrHZpuHvMBBB-DOtnULUa5Q3Z3tpcsfSjBX27OeSSS-VY6vsoVq7nlDYgqmAkD2FF6dpPZTzbqbk00jm0GedeSLIwxku7J3nShS304fsRKiQtLG9ytm6erf9vtgySG2R1Ab0j2Q_mRkifGiFBFSA8SqDTrLXTMJkyzuwGuuJ0F330BivuZ_7j_T5hbeG1gJ5jDNaqjoUG9S1CDZdY-L8j9xKBPXKlTCzuziUrFtovcLVMbrona6s-asEBNCziMxVSvaKONuPSv0JJnZZKLIMJN3-1-QqK-qmx8rLaaBCvYgwzR8RlHEjBlF1SthV3V_VY_yP4qFIuzKAeu0FuGwE034oTS5wnTCigPwFOu927NvQRR_QxNwgyRumOey1eJoEOjGdCJRBiCZp8eElWk9_s2hYtuVZUpMh4eKQM0wWmae4rnmRgSDPfdAqK9Ty1ZAtIKgId2afVGM-F2hNKeOLS_uFS9yMgQMoEYof6HK6rdK0cZPt1WbSoE=w965-h453-no "a biconditional b or c")

User input supports a wide range of symbols and letters to represent atomic sentences.<br/>
#### Examples:
* (a and b) implies c
* a ↔ b v c
* a biconditional b


