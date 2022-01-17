#
**_EXPERIMENT-13_**
##
**_Aim of the Experiment:_**
Write a C++ program for user defined exception.

##
**_Step-by-step process of Experiment:_**<br/>
1.In order to create a custom program, we have included a header file initially along with iostream.<br/>
2.Create exception class.<br/>
3.Here we have created a class MyException which will inherit base class exception.<br/>
4.Inside the exception class  MyException we will have the functions. Here we have the function char* what() which is of const type.<br/>
5.On the next line, we have created two objects one of user defined exception class and one for the exception class.<br/>
6.Then inside try block we have operated the divide functions and if there error occurs in the logic or mathematical operation, we will throw the exception class object.<br/>
7.Inside the catch block, we have included the exception object with its exact address pointer. There we are showing the result by calling what function through the exception object.<br/>
 
