# Welcome READ - 10 

## Error Handeling Debugging 


![](https://cdn3.vectorstock.com/i/1000x1000/96/47/error-pixel-glitch-vector-20409647.jpg)

### JavaScript can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully


* THE CONSOLE & DEV TOOLS  

* COMMON PROBLEMS 

* HANDLING ERRORS 

## ORDER OF EXECUTION

### To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run


## EXECUT.ION CONTEXTS 

### The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope


## UNDERSTANDING SCOPE 

### In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object. 


## UNDERSTANDING ERRORS 

### If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code. 