# **Erorr, handling and debugging**


- If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handling code.
- Error objects can help you find where your mistakes are
and browsers have tools to help you read them.

 # **There are two things you can do with the errors:** 
 <ol>
 <li>Debugd the script to fix errors </li>

 <li>Handel errors gracefully</li>
 
 </ol>

 # Debugging 
 is about deduction eliminating potential causes of an error.

 **Note:**

 - The console helps narrow down the area in which the error is located, so you can try to find the exact error
 - JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
 - If you know that you may get an error, you can handle it gracefully using the try, catch, finally statement
