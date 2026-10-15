# debug_log.md
# Author: Charlize Pineda

## Bug 1
Error type: KeyError
File + line:  File "/home/charl_xqubzfy/ism3232/module05_functions/week8_buggy.py", line 21 and File "/home/charl_xqubzfy/ism3232/module05_functions/week8_buggy.py", line 12
What the error means: It's tring to access a key that doesn't exist because of a typo
What I told the duck: I told the duck the code is supposed to return a total, starting with the records followed by the defined functions, but without returning a total there's a disconnect in the definined functions and the record.
What I tried: Looked up what KeyError meant and based on that I worked backwards - looking at the lines that showed the error before noticed the mistype in the word "amount"
How I fixed it: I spelled amount properly

## Bug 2
Error type: TypeError
File + line:  File "/home/charl_xqubzfy/ism3232/module05_functions/week8_buggy.py", line 23 and File "/home/charl_xqubzfy/ism3232/module05_functions/week8_buggy.py", line 16
What the error means: Using > cannot be done with a string and an integer on both side, they need to both be integers. 
How I fixed it: I removed the ' from around the "1000" to turn it into an integer and make it possible for the comparison to go through

## After Fixing Both Bugs
Final output: Total: $5150.00 across 3 records
True
Did pytest pass? Yes / No

## AI Literacy Reflection
Did I use AI? Yes 
If yes -- exact prompt I used: How do I rename my file
What AI explained: I needed to navigate into the tests folder in order to rename a file. I previously was just in module05_functions trying to rename my test_week8 file and was receiving an error.
What I changed myself: I renamed my file using mv
Can I explain every fixed line? Yes

## What I learned
There were two bugs, the first one was a mistype that resulted in a KeyError and the second one was TypeError due to their being a string and an integer on both sides of a comparison symbol. Through this lab, I learned that VS code identifies errors in a very straightforward manner so its easier to traceback where things might've gone wrong. Along with that, I learned the rubber duck method, which is something I subconsciously do when I review errors in my work, also helps with debugging code.
