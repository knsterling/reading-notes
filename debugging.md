**Error Objects** - Helps you find where your mistakes are.
*name*
*message*
*fileNumber*
*lineNumber*
*error*
*SyntaxError*
*ReferenceError*
*URIError*
*TypeError*
*RangeError*
*EvalError*

**Deduction Process**
To locate bugged codes, right click on the webpage and select 'Inspect' then click on the Console tab.  Inside the tab are the error messages that 
will tell you where exactly the problem lies and what it is.
When building codes anticipate that there might be failure so include the Exception Handles syntax:

// try{
} catch (exception) {
} finally {
} //
Error can occur even after you have a code figured out.



