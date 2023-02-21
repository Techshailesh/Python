*******************************
     Lambda Functions
*******************************

What is a Lambda Function?

Lambda functions are similar to user-defined functions but without a name. 
They're commonly referred to as anonymous functions.


* Lambda functions are efficient whenever you want to create a function that will only contain simple expressions – that is, 
expressions that are usually a single line of a statement. 
* They're also useful when you want to use the function once.

Below is the syntax to define Lambda function:


--> lambda argument(s) : expression


1) lambda is a keyword in Python for defining the anonymous function.
2) argument(s) is a placeholder, that is a variable that will be used to hold the value you want to pass into the function expression. 
 A lambda function can have multiple variables depending on what you want to achieve.
 
3) expression is the code you want to execute in the lambda function.

![Snip20230220_33](https://user-images.githubusercontent.com/93876736/220208420-edb2c93c-712b-4321-9690-40cd40ac9a1a.png)

* We cant use RETURN clause in lambda function, like we do in normal function.
* we cant use multiple lines , not accepted in lambda function.

![Snip20230220_34](https://user-images.githubusercontent.com/93876736/220209142-fc3e1f5a-6251-45b4-aadb-7b00172a9d8b.png)


 ###############  Practical Uses of Python lambda function ###################
 
 
 Python Lambda Function with if-else
 
 ![Snip20230221_35](https://user-images.githubusercontent.com/93876736/220333089-19b74d77-9bd1-4859-8e17-fb77d84a979a.png)
 
 
 ** Lambda functions can be used along with built-in functions like filter(), map() and reduce(). 
 
 Example using filter():
 
 ![Snip20230221_36](https://user-images.githubusercontent.com/93876736/220333872-82aa9dff-9fa7-4aa3-8485-fc5d1720fecd.png)


 
 

