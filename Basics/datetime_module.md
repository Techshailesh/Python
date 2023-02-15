How to work with Date and Time in python :

Python doesnt have any standard moduke for date and time, we have to import the datetime moddule from the python library.
The data time module offers four classes to efficently work with date and time :
 1) date
 2) time
 3) datetime
 4) timedelta

All the objects of these classes are immutable. So once defined, you cannot change it.
However, we can manipulate them and create a new object


                                               ******** DATE ****************

Lets import DATE class from datetime module. 
Once imported , we can use the date class anywhere in this notebook.

It represents a date in the format "YYYY-MM-DD". Constructor of this class needs three mandatory arguments year, month and date.

--Constructor syntax: ----  

class datetime.date(year, month, day)

![Snip20230215_5](https://user-images.githubusercontent.com/93876736/219001083-f8d650d2-90b7-474b-bb75-514db0e9b296.png)


The argument values must be an integer, and they should be within a valid range.
I mean, I cannot supply month value as 13. Similarly, I cannot provide a date value as 32.
The date() function performs a stringent value check and does not allow you to create invalid dates.

Lets see some examples by passing out of range values:

![Snip20230215_3](https://user-images.githubusercontent.com/93876736/218998440-ed050c4f-131b-4156-9a26-e2261926ede2.png)


Other than the date() constructor function, we can  use the "today() function" to create a date.

However, today will give you the current system date.


![Snip20230215_4](https://user-images.githubusercontent.com/93876736/219000790-ef181492-4c6a-443b-8435-d8b870149ecb.png)


![Snip20230215_6](https://user-images.githubusercontent.com/93876736/219002688-a861cdcc-7798-4f7a-8242-9c97c8a0c496.png)

"strftime() function" to format your date and time in the desired string format. 
An example is shown below--


![Snip20230215_7](https://user-images.githubusercontent.com/93876736/219007538-0c34321a-4b5a-462d-ab25-17f9cb8c2cfb.png)

There are many other similar format codes in the Python doc, we can refer that as desired.


                                 ************* TIME **************
                                 

The time class creates the time object which represents local time, independent of any day.

The time function takes four arguments : 

1.Hour

2.Minute

3.Second

4.Microsecond

All the arguments are optional, and the default value is assumed to be zero.


![Snip20230215_12](https://user-images.githubusercontent.com/93876736/219013063-d03f9ef8-bd9d-465a-a931-0891610a5a22.png)


The time() function also implements stringent validation, and you cannot supply invalid values.
See the examples:

![Snip20230215_14](https://user-images.githubusercontent.com/93876736/219014233-996105c7-5b6e-4b2d-8f1c-b8fc91b5a66b.png)


![Snip20230215_15](https://user-images.githubusercontent.com/93876736/219015950-8590c2a9-9312-4c8a-9b31-e64ba68b587c.png)

 
               ********* DATETIME CLASS ******************

The DateTime class contains information on both date and tim. We create this using "datetime()" constructor
      
 ![Snip20230215_17](https://user-images.githubusercontent.com/93876736/219018619-efac2e86-706d-4dd9-9bde-032c94d4d0aa.png)
 
 
 So, the datetime function takes seven arguments:
 
 1.Year
 
 2.Month
 
 3.Date
 
 4.Hour
 
 5.Minute
 
 6.Second
 
 7.Microsecond
 
 The first three arguments are required, and the remaining arguments are optional.
 
 
THE "datetime() function" also implements stringent validation, if we pass invalid values it will fail as we have seen in date and time also.

Once the datetime is defined, you can get all the individual components using the appropriate member attributes.

![Snip20230215_18](https://user-images.githubusercontent.com/93876736/219022034-25772d0f-00eb-4a99-826a-016ee1cf06df.png)


We can also print the current date and time using the Datetime.now() function. now() function returns the current local date and time. 

![Snip20230215_19](https://user-images.githubusercontent.com/93876736/219022959-5819f9e6-b79f-4c51-975d-b360b8d1fe97.png)

                                  ########### Timedelta class #############
                   
Python timedelta class is used for calculating differences in dates and also can be used for date manipulations in Python. 
It is one of the easiest ways to perform date manipulations.

The timedelta represents a duration.For example, you may want to represent 2 days, 3 hours, and 45 minutes. That is a duration. 
We can create this duration using the " timedelta() constructor "

Constructor syntax:  

class datetime.timedelta(days=0, seconds=0, microseconds=0, milliseconds=0, minutes=0, hours=0, weeks=0)

Returns : Date 

![Snip20230215_21](https://user-images.githubusercontent.com/93876736/219066973-7d8d94b4-61c1-4b98-aadf-a2232069827c.png)


We only used days, hours, and minutes earlier, but you can use a combination of other inputs such as weeks, seconds, and even microseconds.

The main usage of this class is to perform arithmetic opertions , we will see some examples:

1) add two dates , we will call as DOB here. We wil notice that add operations is not allowed.


![Snip20230215_23](https://user-images.githubusercontent.com/93876736/219069460-402e99b8-7286-43b5-9022-c5e2642a8467.png)


2) minus two dates, we will notice that this opertion is allowed and it makes sense also . we can get age difference  

![Snip20230215_24](https://user-images.githubusercontent.com/93876736/219069720-1bcce3cf-af26-4d58-8c6f-0d78bc32ef6b.png)



      

                               











