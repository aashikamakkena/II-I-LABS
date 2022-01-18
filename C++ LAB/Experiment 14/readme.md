#
**_EXPERIMENT-14_**
##
**_Aim of the Experiment:_**
Write a C++ program to show rethrowing.

##
**_Step-by-step process of Experiment:_**<br/>
1.When try blocks are nested and a throw occurs in a function called by an inner try block, control is transferred outward through the nested try blocks until the first catch block is found whose argument matches the argument of the throw expression.
2. If error is thrown within the inner try block (in this case, from func2()), the exception is caught by the inner catch block, and, assuming this catch block does not transfer control, func3() is called.
3.If spec_err is thrown after the inner try block (for instance, by func3()), it is not caught and the function terminate() is called.
4.If the exception thrown from func2() in the inner try block is type_err, the program skips out of both try blocks to the second catch block without invoking func3(), because no appropriate catch block exists following the inner try block.

