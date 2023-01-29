Sequences in  Python:
  ------------------------

  A sequence in python refers to an ordered collection of items , in which each element is accesible by its position or index in sequence.
  Python offers you three basic type of sequence type:

    1) List
    2) Tuples
    3) Range
    4) String



Sting also falls in Sequences, because it is an ordered collection of characters, where each character has a unique position or index in the sequence.

![Snip20230129_12](https://user-images.githubusercontent.com/93876736/215327417-042d027f-d197-427e-9a6a-0c32f7732f14.png)



Mutability:
-----------

In python , only  List seqeunce is  "MUTABLE", others are "UNMUTABLE".
What it means that if sequence is mutable then , we can change state or content , if sequence type is immutable , you cannot change its state or content.


We will see some list of common opertaions in sequences:
---------------------------------------------------------


1) Comparison of the same type.


You can compare sequence of same types. lets see examples-

 Comparing strings here :
 -----------------------


![Snip20230129_13](https://user-images.githubusercontent.com/93876736/215327509-364bdc52-04a1-4c83-be87-a65f9cdaa7cb.png)

![Snip20230129_16](https://user-images.githubusercontent.com/93876736/215327947-f923af4b-1477-475d-afdd-ef7219fc675f.png)

Now lets compare some "LIST" types:
----------------------------------

![Snip20230129_17](https://user-images.githubusercontent.com/93876736/215328068-de06aff4-1513-40a8-8398-c792d914ff65.png)


![Snip20230129_18](https://user-images.githubusercontent.com/93876736/215328107-9c6cae67-a42f-4838-a8c9-cb45ebd9a698.png)


-------------------------
2) Containment (in, not in)
-------------------------

A containment test in Python checks if an element is present in a sequence. This is typically done using the 'in' and 'not in' operator.

The in operator works with all sequences , such as tuples, sets, and strings.


![Snip20230129_19](https://user-images.githubusercontent.com/93876736/215345862-cce89fcd-3a7a-4b76-805f-8ac4c052b4a8.png)

Now in above example , In the first containment test on string, we are trying to find ‘h’ in the name. 
Does it exist? No !!!
So the outcome is FALSE. Likewise we did other search.


![Snip20230129_24](https://user-images.githubusercontent.com/93876736/215349366-9c78e00d-286a-4673-9c8b-1e1f6df13559.png)



If x is equal to one of the elements in lst_container, the condition x in lst_container will evaluate to True and the code inside the if block will be executed. If x is not equal to any of the elements in lst_container, the condition will evaluate to False and the code inside the block will not be executed.


![Snip20230129_21](https://user-images.githubusercontent.com/93876736/215348814-2b2de2e5-1952-4f82-954e-38fba7d2f62d.png)



![Snip20230129_23](https://user-images.githubusercontent.com/93876736/215348902-6f7f9334-6802-4c71-a2f1-02c81ac7c0e6.png)


### VERY IMP POINT TO BE NOTICED #####


However, this subsequence search is specially designed for strings. 
So, this one does not work with the list or tuple, and you can see the same in the example below. I am searching for a sequence of one/two names in a name list. 
It does exist. However, you will always get false. No error, no exception. But the FALSE output.
And that's confusing if you do not know that the subsequence search only works with strings. It does not work with lists and tuples

![Snip20230129_27](https://user-images.githubusercontent.com/93876736/215360591-7c29836b-1709-40fb-bc9f-c69844a5124a.png)










 




