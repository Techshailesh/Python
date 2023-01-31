Lets learm some string functionalities:

-------------------------------------------
1.String Literals
-------------------------------------------

what does STRING LITERALs mean ??? 
A string literal can be created by writing a text(a group of Characters ) surrounded by a single(”), double(“”), or triple quotes.  By using triple quotes we can write multi-line strings or display them in the desired way. 

we can create a string literal using single or double-quotes. Why do we have two options? 
This flexibility helps us to create strings that contain a single quote or double quote within the string literal. 

In quote 1 , we can see that I have used '' literal and within that tried to include " " , it accepted.
but in quote 2 , when i have used " " and again tried to include " " , it not accepted. 
likewise in other example

![Snip20230131_2](https://user-images.githubusercontent.com/93876736/215753667-abda3fa1-7189-42e3-88a8-e795e095766c.png)




we also have triple quotes. You can use either three single quotes or three double-quotes to create multi-line strings. Here is an example shown 

![Snip20230131_3](https://user-images.githubusercontent.com/93876736/215755766-8f1c2de7-77a9-46cd-ac0f-039ae3cd1034.png)


** Using backslash(/) to include special characters in literals **

We can also use a backslash to escape special characters in a Python string. Here is an escaping example shown below. We have escaped the single quotes using the backslash character. 
What if we don't use the backslash character? Well, it will give me an error saying invalid syntax. It is because the string ended here, so it doesn't understand the remaining part of the string.



![Snip20230131_4](https://user-images.githubusercontent.com/93876736/215756439-c976035a-2916-457d-b69d-72dd6be0ed83.png)


** Adding new line using \n **

We can also add a new line or some extra spaces in the string using the escape character as shown below

![Snip20230131_5](https://user-images.githubusercontent.com/93876736/215758255-cfd8ccfc-596f-4fb4-9247-bff743093a55.png)

#################################################################################################################################

-----------------
2- STRING FUNCTIONS
-----------------

1) SPLIT FUNCTION

   You use the .split() method for splitting a **string** into a **list**. The primary goal is to splitting a string and getting into a list

The general syntax for the .split() method looks something like the following:

**string.split(separator, maxsplit)**


-string is the string you want to split. This is the string on which you call the .split() method.
-The .split() method accepts two arguments. (optional)





![Snip20230131_6](https://user-images.githubusercontent.com/93876736/215760231-1cf5e7e4-a89c-47c5-a6fa-4548740fafae.png)


When you don't pass either of the two arguments that the .split() method accepts, then by default, it will split the string every time it encounters whitespace until the string comes to an end.

Now when we check the type of object the original type is STR and the splitted type is LIST.

So primarly thats the whole purpose.

Lets check anther scenario below.

![Snip20230131_7](https://user-images.githubusercontent.com/93876736/215761912-4ad83238-47da-465f-baa2-f8702e0afe15.png)


In the example above, I added consecutive whitespaces between the word love and the word coding. When this is the case, the .split() method treats any consecutive spaces as if they are one single whitespace.

Now lets try to add separator clause in the spli function formula:

The separator will break and divide the string whenever it encounters the character you specify and will return a list of substrings.

For example, you could make it so that a string splits whenever the .split() method encounters a dot, .

![Snip20230131_10](https://user-images.githubusercontent.com/93876736/215763542-d22ba6cd-8a13-4951-808b-9c7d3a0ab85e.png)

2) JOIN FUNCTION-

This is just precisley opposite of Split functions . Here, you provide a list as an input and get a string as an output.

![Snip20230131_11](https://user-images.githubusercontent.com/93876736/215766366-7ed1ff66-44d4-4d1f-98ce-bba0eb3a4f71.png)











