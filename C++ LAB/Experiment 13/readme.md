#
**_EXPERIMENT-13_**
##
**_Aim of the Experiment:_**
Write a C++ program for user defined exception.





 In order to create a custom program, we have included a header file initially along with iostream.
 create exception class
  Here we have created a class, named as Divide_By_Zero which will inherit base class exception.
  Inside the exception class, Divide_By_Zero, we will have the functions. Here we have the function char* what() which is of const type.
  On the next line, we have created two objects one of user defined exception class and one for the exception class.
  Then inside try block we have operated the divide functions and if there error occurs in the logic or mathematical operation, we will throw the exception class object
   Inside the catch block, we have included the exception object with its exact address pointer. There we are showing the result by calling what function through the exception object.
 
