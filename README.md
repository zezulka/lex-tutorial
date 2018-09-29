The following steps need to be gone to get the desired executable:
0. Install lex (tested on the flex package)
1. ```lex myscanner.l```, this produces a lex.yy.c file needed in the next step
2. ```gcc myscanner.c lex.yy.c -o myscanner```
3. The ```myscanner``` executable is then feeded the appropriate input from stdin.
