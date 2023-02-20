Below is a simple example of defining function and calling it.

I have defined Function "menu"  and have  called with required arguments ie 3  and result is diplayed as below


![Snip20230219_5](https://user-images.githubusercontent.com/93876736/219965117-985c270f-7d6e-495e-83a9-43cd4db5d112.png)

We cannot pass less or more noumber of arguments when calling function , we will get postional argument error see example below:


![Snip20230219_4](https://user-images.githubusercontent.com/93876736/219965367-bd5b337f-d154-4fa4-b1b5-b8c77729e90f.png)

***********************************************************************************************************************************************
Function parameters are of two types:

1.Mandatory Parameters

2.Optional Parameters 

If we want to make a function parameter optional, you must set a default value for the parameter, and it becomes optional.
If we do not set a default value, the parameter remains mandatory.


We have this flexibility to define three arguments and just pass 1 or two values.

I have changed the menu() function by changing the third parameter to have a default value ie Desert="Sweet".

Which means that I can call function with just two arguments

![Snip20230219_6](https://user-images.githubusercontent.com/93876736/219967774-e019c551-19fc-4aab-a200-b9f4b0955ad5.png)

So when I am passing just two argumnents , third argument takes default value defined in menu function ie : desert="Sweet".


I can also call function with all three arguments in same example.

![Snip20230219_7](https://user-images.githubusercontent.com/93876736/219967923-fbcf47bb-ce8e-4e75-bcff-d02b7bd742c2.png)




Similarly , when I am passing all three arguments , function accepts the input passed execlusively , not default . So Dessert = "Ice cream" here.

I can have all 3 arguments as default , as shown below:

![Snip20230219_8](https://user-images.githubusercontent.com/93876736/219968779-484880b8-f5af-4c95-bead-fd446b09bd7e.png)


######################################################################################################################################

Lets see some complex scenarios now :


Lets say I just want to change Main and Dessert in menu for this week, and I want starter to be default. 

Lets see in practical.

![Snip20230219_9](https://user-images.githubusercontent.com/93876736/219969370-0f359020-8689-4bd5-af43-2aef4bf9a938.png)

Oops !!! it failed. I passed two values , logically it should take but unfortunately no.

Here I tried to make the first parameter as optional. But I got an error "-the non-default argument follows the default argument"


Rule:
 It means I cannot have a mandatory parameter after an optional parameter.
 And the rule is simple. Define all your mandatory parameters and then add your optional parameters in the end.
 If I want to make Starter an optional parameter, I must place it in the end as shown below
 
 
 ![Snip20230219_13](https://user-images.githubusercontent.com/93876736/219970824-586f498f-d0dc-4af6-84e5-2ee378ec4d29.png)
 


I have two default values, and both of these are in the end

![Snip20230219_14](https://user-images.githubusercontent.com/93876736/219971397-47f1b1e0-d51f-43be-bea3-e48de532b80f.png)


########################################################################################################################################

Lets see second scenario :


When I am trying to pass key based value , it failed , see the example below .

![Snip20230219_16](https://user-images.githubusercontent.com/93876736/219972760-2e2b888f-cc6d-4cab-93c6-06bd0b3c6db2.png)


So, we have one more rule.
While calling a function, all our key/value arguments should be in the end.
So, I can call this function with the parameters as key/value like this.

![Snip20230219_18](https://user-images.githubusercontent.com/93876736/219972935-83c18a2a-f7f8-4f1c-aafc-3301a212942d.png)


![Snip20230219_19](https://user-images.githubusercontent.com/93876736/219973091-7e4d0be0-c55f-48d2-83f5-78eb85e0b60c.png)


![Snip20230219_20](https://user-images.githubusercontent.com/93876736/219973736-4aa14c33-0dd5-4284-9a97-6e2a05c2c984.png)


 ***********SO IMP FINAL POINTS *************************:


1) Define all your mandatory arguments first and then add all your optional arguments.

2) Call the function passing all the mandatory arguments by position. Then pass the optional arguments using the key/value pair.


*****************************************************************************************************************************************************
                                                **Variable Length Arguments**
****************************************************************************************************************************************************










