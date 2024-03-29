***Python Collections (Arrays): *******

There are four collection data types in the Python programming language:

List is a collection which is ordered and changeable. Allows duplicate members.

Tuple is a collection which is ordered and unchangeable. Allows duplicate members.

Set is a collection which is unordered, unchangeable*, and unindexed. No duplicate members.

Dictionary is a collection which is ordered** and changeable. No duplicate members.


*************************************************************************************************************************************


What is SET in python ??

Sets is used to store multiple items in single variable.

**Set values are immutable which means we cannot alter the values after their creation **

Set is unordered, unchanged and unindexed.


Sets are written with curly braces {}. Now we have seen this {} in dictionary, dictionary holds key:value pairs , however sets hold collection of unique elements only.


basic example of set :

 A set can have any number of items and they may be of different types (integer, float, tuple, string etc.).
 
 --But a set cannot have mutable elements like lists, sets or dictionaries as its elements.
 
 ![Snip20230214_51](https://user-images.githubusercontent.com/93876736/218708307-f7c0bd79-c296-417f-a08e-abaa858a70da.png)
 
 
 DUPLICATES NOT ALLOWED
 
 ![Snip20230214_53](https://user-images.githubusercontent.com/93876736/218711292-28fca05b-1bfe-49a1-939e-5c072eaddb0b.png)
 
 Removing duplicates from List and tuple:

![Snip20230214_55](https://user-images.githubusercontent.com/93876736/218715854-c6830846-dec1-4366-a2a3-be66a94d3bfd.png)


lower() usecase:

![Snip20230214_58](https://user-images.githubusercontent.com/93876736/218730031-5d69ed0e-a73d-430d-9787-529576798ae9.png)






### Create an Empty Set in Python ##

Creating empty set is bit tricky beacuse if we use {} python will take it as Dictionary. See example below, so we have to use SET to create empty set .



![Snip20230214_56](https://user-images.githubusercontent.com/93876736/218719189-fa529306-db0e-4a38-a25c-bd4ebc1d7443.png)



** len() function: To determine how many items a set has.
   
   ![Snip20230214_60](https://user-images.githubusercontent.com/93876736/218730786-9011b3a3-6609-4bca-b460-4847be0a9282.png)
   
   
 
 ** Python built in comon functions:
 
 The first one is the add() method.Sets are mutable. 
 So you can add an element in an existing set. However, the add() method allows you to add a single element at a time.
 
 ![Snip20230214_61](https://user-images.githubusercontent.com/93876736/218733860-faef5ff0-cdb9-43d5-a5b2-8e4ea489cc27.png)
 
 
 
 --Update()

![Snip20230214_62](https://user-images.githubusercontent.com/93876736/218736130-cda3ce67-47c5-47a4-88a2-54f55854254e.png)

![Snip20230214_64](https://user-images.githubusercontent.com/93876736/218736866-33a8e052-a4de-44c5-ae7f-4a3803f7ea2d.png)

--Remove iteam from set:


![Snip20230214_66](https://user-images.githubusercontent.com/93876736/218740597-7a0f57b6-91f7-4450-b852-89e23fc129a6.png)




**********. Python Set Operations ****************

Union of Two Sets:

1) The union of two sets A and B include all the elements of set A and B.

![Snip20230214_67](https://user-images.githubusercontent.com/93876736/218743850-dd522a76-d950-45cf-b597-23b2bb860a01.png)


2) Set Intersection:

The intersection of two sets A and B include the common elements between set A and B.

![Snip20230214_68](https://user-images.githubusercontent.com/93876736/218744386-c863c495-4789-4f34-a797-3ea919ea4824.png)


3) Difference between Two Sets:

The difference between two sets A and B include elements of set A that are not present on set B.

![Snip20230214_69](https://user-images.githubusercontent.com/93876736/218745755-8b0d8679-4d46-452b-88fb-2d2e45aff491.png)



4) Set Symmetric Difference:

The symmetric difference between two sets A and B includes all elements of A and B without the common elements.

![Snip20230214_70](https://user-images.githubusercontent.com/93876736/218746323-c1bb6253-88e1-483a-818e-18bcb20f666e.png)


Check if two sets are equal:

We can use the == operator to check whether two sets are equal or not. For example,

![Snip20230214_71](https://user-images.githubusercontent.com/93876736/218749252-52d6779b-d0c9-41b1-bf20-5ee95d3f92a7.png)


Containment test in set :

 we can check if element exists or not using IN function. Example 
 
 ![Snip20230214_72](https://user-images.githubusercontent.com/93876736/218750030-6ef31aa0-3f01-4103-9265-bdb6a41b0849.png)

 
 
 We can also check many other operations such as superset ,subset . refer document.
 
 ![Snip20230214_73](https://user-images.githubusercontent.com/93876736/218751228-66d0aaf0-5c4c-46f4-b17a-d1508909fcf3.png)



## So when you are using Python sets in your program, think of them as a mathematical set and look for the methods to get things done.Most likely, you will find a function or a method to achieve your goal.##

Element extraction in SET:

All that element extraction and slicing that we learned in the earlier data types will not apply to SET. 

Why? Because the sets do not have an index.

![Snip20230214_74](https://user-images.githubusercontent.com/93876736/218774315-9797dbb1-d949-449b-b523-b870dfddaf75.png)



Then how do we access the elements of a set? Well, you must loop through it. You should notice the order of elements. It comes like jumbled. This happens because sets are an unordered collection of unique elements. And they do not have an index. 


![Snip20230214_75](https://user-images.githubusercontent.com/93876736/218774530-83768d9c-74d3-4d3a-971a-b13db1bd1e0d.png)


************ FROZENSET *******************

Set elements are immutable but the set itself is a mutable object, so in order to make an immutable set, we use the concept of frozenset. The frozen set returns an immutable version of a Python set object.

We can modify the elements of a set at any time by adding or deleting elements, but "frozen sets" do not allow any modification after its creation. Frozenset can be applied on any iterable. A frozenset is similar to a set object, therefore, the order of an element is not guaranteed to be preserved.

![Snip20230214_77](https://user-images.githubusercontent.com/93876736/218788025-a1f5b077-4125-493c-aa6f-3192a5a6078f.png)



