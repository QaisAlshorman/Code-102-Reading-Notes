### ORDER OF EXECUTION 
To find the source of an error, it helps to know how scripts are processed. 
The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.
### EXECUTION CONTEXT 
 
Every statement in a script lives in one of three execution contexts: 
- GLOBAL CONTEXT 
Code that is in the script, but not in a function. There is only one global context in any page. 
- FUNCTION CONTEXT 
Code that is being run within a function. Each function has its own function context. 
- EVAL CONTEXT (NOT SHOWN) 
Text is executed like code in an internal function called eva l . 

#### VARIABLE SCOPE 
The first two execution contexts correspond with the notion of scope :
- GLOBAL SCOPE 
If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope. 
-FUNCTION-LEVEL SCOPE 
When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope.

![image](https://user-images.githubusercontent.com/85091281/124329842-de878c00-db94-11eb-9b28-c03cefb38f9f.png)
![image](https://user-images.githubusercontent.com/85091281/124329904-fe1eb480-db94-11eb-9890-8e7defea42e3.png)

#### EXECUTION CONTEXT & HOISTING 
Each time a script enters a new execution context, there are two phases of activity: 

1: PREPARE 
• The new scope is created 
• Variables, functions, and arguments are created 
• The value of the this keyword is determined

The preparation phase is often described as taking all of the variables and functions and hoisting them to the top of the execution context. Or you can think of them as having been prepared. 
Each execution context also creates its own vari ab 1 es object. This object contains details of all of the variables, functions, and parameters for that execution context.

2: EXECUTE 
• Now it can assign values to variables 
• Reference functions and run their code 
• Execute statements

If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handl ing code. 

![image](https://user-images.githubusercontent.com/85091281/124330823-dcbec800-db96-11eb-9844-1dc1dab7f780.png)

###HOW TO DEAL WITH ERRORS 
Now that you know what an error is and how the browser treats them, there are two things you can do with the errors. 

1: DEBUG THE SCRIPT TO FIX ERRORS 
If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it. 

2: HANDLE ERRORS GRACEFULLY 
You can handle errors gracefully using try, catch, throw, and fina1ly statements.

Debugging is about deduction: eliminating potential causes of an error. 

WHERE IS THE PROBLEM? 
First, should try to can narrow down the area where the problem seems to be. In a long script, this is especially important. 
1. Look at the error message, it tells you: 
• The relevant script that caused the problem. 
• The line number where it became a problem for the interpreter.
2. Check how far the script is running. Use tools to write messages to the console to tell how far your script has executed. 
3. Use breakpoints where things are going wrong. They let you pause execution and inspect the values that are stored in variables. 

WHAT EXACTLY IS THE PROBLEM? 
Once you think that you might know the rough area in which your problem is located, you can then try to find the actual line of code that is causing the error. 
1. When you have set breakpoints, you can see if the variables around them have the values you would expect them to.
2. Break down I break out parts of the code to test smaller pieces of the functionality. 
• Write values of variables into the console. 
• Calrfunctions from the console to check if they are returning what you would expect them to. 
• Check if objects exist and have the methods I properties that you think they do. 
3. Check the number of parameters for a function, or the number of items in an array.

![image](https://user-images.githubusercontent.com/85091281/124332034-2a3c3480-db99-11eb-804e-e38eef417c7b.png)

If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code. 
Debugging is the process of finding errors. It involves a process of deduction. 
The console helps narrow down the area in which the error is located, so you can try to find the exact error. 
JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.


