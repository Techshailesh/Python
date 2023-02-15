How to work with Date and Time in python :

Python doesnt have any standard moduke for date and time, we have to import the datetime moddule from the python library.
The data time module offers four classes to efficently work with date and time :
 1) date
 2) time
 3) datetime
 4) timedelta

All the objects of these classes are immutable. So once defined, you cannot change it.
However, we can manipulate them and create a new object



Lets import DATE class from datetime module. 
Once imported , we can use the date class anywhere in this notebook.

It represents a date in the format "YYYY-MM-DD". Constructor of this class needs three mandatory arguments year, month and date.

--Constructor syntax: ----  

class datetime.date(year, month, day)

![Snip20230215_2](https://user-images.githubusercontent.com/93876736/218996673-6c7201d1-9473-4640-8555-610b29fa7a2c.png)

The argument values must be an integer, and they should be within a valid range.
I mean, I cannot supply month value as 13. Similarly, I cannot provide a date value as 32.
The date() function performs a stringent value check and does not allow you to create invalid dates.

Lets see some examples by passing out of range values:

![Snip20230215_3](https://user-images.githubusercontent.com/93876736/218998440-ed050c4f-131b-4156-9a26-e2261926ede2.png)




