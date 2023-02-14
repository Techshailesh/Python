***Python Collections (Arrays): *******

There are four collection data types in the Python programming language:

List is a collection which is ordered and changeable. Allows duplicate members.

Tuple is a collection which is ordered and unchangeable. Allows duplicate members.

Set is a collection which is unordered, unchangeable*, and unindexed. No duplicate members.

Dictionary is a collection which is ordered** and changeable. No duplicate members.


*************************************************************************************************************************************


What is SET in python ??

Sets is used to store multiple items in single variable.
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



 
 
 


