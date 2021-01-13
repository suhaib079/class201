# error handling 
This chapter will help you learn how to find the errors in your code It will also teach you how to write scripts that deal with potential errors gracefully. 
### order of execution
> function greetUser () {
>O return 'He 11 o ' + getName ();
>0
>function getName() {
>var name= 'Molly ' ;
>return name;
>_, var greeting= greetUser();
>e al ert(greeting);

This script above creates a greeting message, then writes it to an alert box (see right-hand page). **In order to create that greeting**, two functions are used: 
1. The greeting variable gets its value from the
greetUser() function. 
2. greetUser() creates the message by combining
the string 'He 11 o ' with the result of getName ().
3.  getName () returns the name to greetUser(). 

## EXECUTION CONTEXT & HOISTING
1.  PREPARE
• The new scope is created
• Variables, functions, and arguments are created
• The value of the this keyword is determined
2. EXECUTE
• Now it can assign values to variables
• Reference functions and run their code
• Execute statements 

## ERROR OBJECTS CONTI NUED
#### Syntax Error This is caused by incorrect use of the rules of the language. It is often the result of a simple typo.
#### Ref erenceError
VARIABLE DOES NOT EXIST This is caused by a variable that is not declared or is out of scope.
 
