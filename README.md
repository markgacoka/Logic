# Logic
Logic Code for Formal Analysis

Code for printing a truth table of an argument with any number of logic connectives or atomic sentences.

### Sample 1:
Enter your logical statement e.g. (a and b) implies c / a ↔ b v c / a biconditional b

 *Ensure there is space between the atomic sentences and the connectives!!*
> **not a and b or c implies (d)**

This is your input: not a and b or c implies (d)
Your logical statement has 4 atomic sentences.
+-------+-------+-------+-------+------------------------------+
|   a   |   b   |   c   |   d   | not a and b or c implies (d) |
+-------+-------+-------+-------+------------------------------+
|  True |  True |  True |  True |             True             |
|  True |  True |  True | False |             True             |
|  True |  True | False |  True |             True             |
|  True |  True | False | False |             True             |
|  True | False |  True |  True |             True             |
|  True | False |  True | False |             True             |
|  True | False | False |  True |             True             |
|  True | False | False | False |             True             |
| False |  True |  True |  True |            False             |
| False |  True |  True | False |            False             |
| False |  True | False |  True |            False             |
| False |  True | False | False |            False             |
| False | False |  True |  True |            False             |
| False | False |  True | False |            False             |
| False | False | False |  True |            False             |
| False | False | False | False |            False             |
+-------+-------+-------+-------+------------------------------+

### Sample 2:
Enter your logical statement e.g. (a and b) implies c / a ↔ b v c / a biconditional b

 *Ensure there is space between the atomic sentences and the connectives!!*
> **a ↔ b v c**

This is your input: a biconditional b or c
Your logical statement has 3 atomic sentences.
+-------+-------+-------+------------------------+
|   a   |   b   |   c   | a biconditional b or c |
+-------+-------+-------+------------------------+
|  True |  True |  True |         False          |
|  True |  True | False |         False          |
|  True | False |  True |         False          |
|  True | False | False |         False          |
| False |  True |  True |         False          |
| False |  True | False |         False          |
| False | False |  True |         False          |
| False | False | False |         False          |
+-------+-------+-------+------------------------+

User input supports a wide range of symbols and letters to represent atomic sentences.<br/>
#### Examples:
* (a and b) implies c
* a ↔ b v c
* a biconditional b


