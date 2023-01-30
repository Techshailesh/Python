 :beers:


:fork_and_knife:Element extraction and Slicing :knife:
-------------------------------------------------------

What does it mean? That means we want to extract one or more elements from the sequence using "INDEXING"

Indexing is the process of accessing a single element in a sequence by specifying the index in square brackets ([]). The index starts from 0, so the first element has an index of 0, the second element has an index of 1, and so on. 

Let's try to extract an element from the car string.You can get any element giving an index position of the element in a square bracket. So in this example, I am extracting the second element from my car and so on.


![Snip20230130_34](https://user-images.githubusercontent.com/93876736/215503230-256d4ad9-573e-4afa-8ad0-890e0a1c7180.png)



Now as we know that indexing starts with 0 , when we do negative indexing it starts in reverse way but from **-1**. 
In below exmaple we can see it is extracting in reverse index location , reverse index location always starts with -1.

![Snip20230130_35](https://user-images.githubusercontent.com/93876736/215505730-c75d81bb-e13d-4991-8bb5-2cfb29fe30c1.png)

:point_right:The other way to understand reverse indexing can be that just minus the desired index position with the length. 
What I mean is that , lets say I am searching for airline[-4], so length(15) minus -4 =11 , so if we count from 0 till 11 , we get same result(which is w) 



:eye: Imp point to be considered is that we cannot cross index boundary , if we try to search anything beyond index limit we will be getting error

![Snip20230130_39](https://user-images.githubusercontent.com/93876736/215511426-ded8ad75-c1e7-4815-9cbb-04584c7cd33b.png)

:brain:  
      Same logic works with LIST also, below example is easy to underdstand.

![Snip20230130_40](https://user-images.githubusercontent.com/93876736/215514007-e6ae64ce-9523-459f-b027-876d9b5935a5.png)


 :star_struck: Till now we have seen examples to extract single element, But what if we want to extract multiple elements? Lets proceed :point_down:
 
 
The slicing syntax follows below pattern:

![image](https://user-images.githubusercontent.com/93876736/215524189-bfa6ba2e-8e7f-4db2-b6bf-7849c80b3996.png)


It means that, give me the slice of object, starting from ‘start_index’, up to the ‘stop_index’ with a given ‘step_size.’

![Snip20230130_41](https://user-images.githubusercontent.com/93876736/215523441-df856d86-48c7-4a82-afcc-0831a81a9bdc.png)



