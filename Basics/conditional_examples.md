
                                          -----PYTHON CONDITIONAL STATEMENTS ---------


**************
Type 1 : IF
**************

We start with the "if" keyword. Then we have a specific condition, and finally, a "colon" to mark the end of the condition.If the condition is true, Python is going to execute the block of code under the if statement.


Example 1:
--------------

  ![Snip20230127_6](https://user-images.githubusercontent.com/93876736/215062332-f9221838-2a43-4d5d-970d-2d2b2c667774.png)



Explanation: 

  Here is an example of the if statement.The value of ‘a’ is 5 which is greater than zero. So, the indentation below the if statement identifies the statements to execute if the condition is true. 
  The last line is outside the if block, and hence it is going to be executed irrespective of the condition. And we can see the same in the output.


Example 2:
------------



 ![Snip20230127_7](https://user-images.githubusercontent.com/93876736/215063042-5eacba49-6d06-4461-ac23-904bed2e5a85.png)




Explanantion: 
------------

  Now, I have changed the value of ‘a’ to -3, now ‘a’ is less than 0.
  So,the if block is not executed and only this last print statement is evaluated in the output. 
 None of the statements under if indentation got executed , because a is less then zero.
 
 


*****************
Type 2: if-else
*****************
  
when the condition is true, Python is going to execute the first block, and if the condition evaluates to false, it is going to run the second block. 
And the last line or anything below this bock will execute anyway.


code :
------

 ![Snip20230127_8](https://user-images.githubusercontent.com/93876736/215066433-2896e270-e0dd-4e8a-ad28-0ea27a8c36b5.png)




code:
-----

![Snip20230127_9](https://user-images.githubusercontent.com/93876736/215066811-d9d2eae7-501a-4126-a104-78d327b2cddf.png)

    print("I am inside the else block")


***************************
Type 3 :  the "ELIF" ladder
*************************** 


![Snip20230127_10](https://user-images.githubusercontent.com/93876736/215067391-e40caa1b-c775-4aef-aac0-ee48d0785551.png)

It checks the first condition for a greater than 0, if the condition is true, the statement under that block is executed. 
Otherwise if the condition is false, 
it checks the second condition and again if the condition is true, the statement under that block is executed. 
Even if this condition is false, the statement under the else block is executed. 
