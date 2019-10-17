# Logic
Logic Code for Formal Analysis <br/>

Code for printing a truth table of an argument with any number of logic connectives or atomic sentences.

### Sample 1:
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

### Sample 2:
Enter your logical statement e.g. (a and b) implies c / a ↔ b v c / a biconditional b

 *Ensure there is space between the atomic sentences and the connectives!!* <br/>
> **a ↔ b v c** <br/>

This is your input: a biconditional b or c  <br/>
Your logical statement has 3 atomic sentences. <br/>
+-------+-------+-------+------------------------+ <br/>
|   a   |   b   |   c   | a biconditional b or c | <br/>
+-------+-------+-------+------------------------+ <br/>
|  True |  True |  True |         False          | <br/>
|  True |  True | False |         False          | <br/>
|  True | False |  True |         False          | <br/>
|  True | False | False |         False          | <br/>
| False |  True |  True |         False          | <br/>
| False |  True | False |         False          | <br/>
| False | False |  True |         False          | <br/>
| False | False | False |         False          | <br/>
+-------+-------+-------+------------------------+ <br/>

User input supports a wide range of symbols and letters to represent atomic sentences.<br/>
#### Examples:
* (a and b) implies c
* a ↔ b v c
* a biconditional b


