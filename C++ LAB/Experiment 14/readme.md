#
**_EXPERIMENT-14_**
##
**_Aim of the Experiment:_**
Write a C++ program to show rethrowing.

##
**_Step-by-step process of Experiment:_**<br/>
1.When try blocks are nested and a throw occurs in a function called by an inner try block, control is transferred outward through the nested try blocks untill the first catch block is found whose argument matches the argument of the throw expression.<br/>
2. If error is thrown within the inner try block, the exception is caught by the inner catch block, and, assuming this catch block does not transfer control.<br/>
3.If error is thrown after the inner try block , it is not caught and the function terminate() is called.<br/>
4.If the exception thrown  in the inner try block is error, the program skips out of both try blocks to the second catch block without invoking because no appropriate catch block exists following the inner try block.<br/>

