    #########    Dictionary  ##############
    
    
Dictionaries are used to store data values in key:value pairs.

A dictionary is a collection which is ordered*, mutable and do not allow duplicates.

Dictionaries are written with curly brackets, and have keys and values:


![Snip20230213_33](https://user-images.githubusercontent.com/93876736/218460668-bb5f3abc-8d17-44f9-b906-22393bf71f84.png)


----Ordered or Unordered? -----


As of Python version 3.7, dictionaries are ordered. In Python 3.6 and earlier, dictionaries are unordered.

When we say that dictionaries are ordered, it means that the items have a defined order, and that order will not change.

Unordered means that the items does not have a defined order, you cannot refer to an item by using an index.



Changeable
Dictionaries are changeable, meaning that we can change, add or remove items after the dictionary has been created.

Duplicates Not Allowed

![Snip20230213_34](https://user-images.githubusercontent.com/93876736/218463155-a9f13fb5-62aa-404a-b041-bfac7877a9ad.png)


Dictionary Items - Data Types

The values in dictionary items can be of any data type:


![Snip20230213_35](https://user-images.githubusercontent.com/93876736/218464023-5b43165e-c0bd-4ea4-be05-4913bc958051.png)



How to access KEYS in dictionary: ????

NOTE: indexing doesnt work in dictionary unlike list,tuples.

![Snip20230213_36](https://user-images.githubusercontent.com/93876736/218468578-c31b194e-4ae7-4e32-8a44-70a8b0c7a2a2.png)



Some built in fucntion to access dictionary:

![Snip20230213_40](https://user-images.githubusercontent.com/93876736/218481044-d8a6bc33-12e6-42ca-b9ba-59027b03d1f4.png)



### Mutability examples  ####

Add values:

Add Elements to a Python Dictionary
We can add elements to a dictionary using the name of the dictionary with []. For example,


![Snip20230213_37](https://user-images.githubusercontent.com/93876736/218472404-009a554d-e70a-4630-9da1-c651e3c5b7b7.png)



Change value in dictionary :

![Snip20230213_38](https://user-images.githubusercontent.com/93876736/218473122-280c0393-a2be-4dd0-9dba-2aa0244cf9d0.png)



Update Dictionary:

The update() method will update the dictionary with the items from the given argument.

The argument must be a dictionary, or an iterable object with key:value pairs.

![image](https://user-images.githubusercontent.com/93876736/218476018-27b3f0a6-cf43-4404-b55a-c074400dae78.png)


### Merging dictionary ###

We merge dictionary using  "double asterisk" . if they both have duplicate key , then currwnt value will be captured.

![Snip20230213_43](https://user-images.githubusercontent.com/93876736/218508134-74f657b5-b2e6-4e90-bddf-71eb32d054ff.png)


Some common used operations in dictionary (refer document) :

len()
clear()
del()
pop()
== operator is used to compare two dictinoary
copy()


** Membership testing in Dictionary

![Snip20230213_44](https://user-images.githubusercontent.com/93876736/218519505-1fe08ab9-fd19-40ad-9a43-35224d49207e.png)



*** Dictionary comprehension **** 

Dictionary Comprehension can be super helpful in creating new dictionaries from existing dictionaries and iterables.


![Snip20230213_49](https://user-images.githubusercontent.com/93876736/218529257-53ad710f-5e5f-4f38-afc0-d1078637969e.png)


Using Dictionary Comprehension
From the above example, we can see that dictionary comprehension should be written in a specific pattern.

The minimal syntax for dictionary comprehension is:

![Snip20230213_47](https://user-images.githubusercontent.com/93876736/218528434-f6e45da9-dce5-45c8-a3e8-8e0bccdddbad.png)
























