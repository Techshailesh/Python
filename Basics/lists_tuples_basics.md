                           :bulb: Working with list and tuples

A tuple is a collection of Python objects separated by commas, which is similar to a List. The most crucial difference between the two of them is the mutability. 


:white_check_mark: list is a mutable object. We enclose lists in square brackets [].

:negative_squared_cross_mark: A tuple is immutable. We enclose tuples in parentheses().

*The elements inside a list or a tuple can be of a heterogenous type, which means you can mix different types of objects 


![Snip20230210_14](https://user-images.githubusercontent.com/93876736/218103608-e20fc0a2-55f1-40d8-8596-84b4ef11dcf2.png)


-- Lets do mutability test ---


 :white_check_mark:  We can see that when we tried to add value in list , it succeded . 

:x: But it failed in Tuple , refer example below





![Snip20230210_19](https://user-images.githubusercontent.com/93876736/218107361-f9e81372-374d-4e77-8651-cfab761a24c5.png)


:bangbang:  But it doesn't mean that we cannot change the Tuple. Using sequence operations such as slicing, concatenating, and extracting elements . All those operations apply to tuples. However, all of them will give you a new Tuple.


