# DEBUGGING TIPS AND TECHNIQUES

DEBUGGING - Debugging is a series of techniques that programmers use to solve a bug in their code.

When you find a BUG in your code :

DON'T GET PANIC

DON'T GET ANGRY

DON'T GET IRRITATED

How to find it there's a BUG ?

- We can find a bug if the code which we have written is not working at all or not working as you want.
- If our screen where we see the output is black, understand that there's a bug in the code.

When debugging, check the console log for errors. If there are any error messages in the console, they often tell you what happened and why this error occurred.

You can open the console in by pressing Ctrl + Shift + J. Often you can fix the errors in your code by reading these error messages. 

The most common errors are:

 1) Typographical: You accidentally misspelled a variable or a function name which the computer doesn't understand. 

2) Incorrect Use of function: You used a function in a way it wasn't intended to be used. 

3) Using variables outside their scope: If you are using variables outside their scope, the computer wouldn't know the value of these variables

The techniques which will help you identify what is causing the bug or which section of your code is leading to this bug: 

1) Commenting sections of your code: You can comment on certain sections of your code to simplify your code and check if your code still throws errors. In this way, you can narrow down to the part of the code which is causing this error. 

2) Printing values of variables in the console: You can print the values of critical variables in the console to visually see how they are changing in the code. If they are not changing as you intend them to, there is something unexpected happening. You can manipulate the variable values to identify what is happening. 

3) Print messages in your code: You can print messages in your code to visually understand how the code is running. For example; you can print messages in the console to understand if while executing the code, an if block is getting executed or the else block. 

You can also combine all the 3 steps. 

Before running the code, one should always have what they expect in their mind and see the difference between what's actually happening.