# UFO_Sightings

### Project Overview

The objective of this project was to build a webpage with the use of HTML, CSS, Bootstrap, and Javascript. The end goal was to aesthetically display UFO sighting data on a dynamic table where a user could input value's into the search filter and the table would adjust according to the filter inputs. The input data of UFO sightings was in javascript form containing a list with many objects and objects with several properties. The code to format the table was written in Javascript, along with that more code was written to detect a user input in the input boxes encoded in the html file and adjust the filters for the table with respect to the input. 
The filters available to the user were 
* Date
* City 
* State
* Country
* Shape

### Results
A simple webpage was built where the user does not have to do much in order to filter the data to their liking. 
The page automatically loads the entire UFO sighting data onto the page. 

To navigate a search simply scroll down to the Filter Search area. 

![image](https://user-images.githubusercontent.com/85713568/138876217-7d126eac-7f33-45da-80b2-b58d249d6e6f.png)

Enter filter value's as you please. Note: The table only contains dates from from 1/1/201 - 1/13/2010 and must be written in placeholder format (1/10/2010), for example 01/01/2010 will not yield a result. Other things to note the other fields are case sensitive city, state, country, and shape must be lowercase.

![image](https://user-images.githubusercontent.com/85713568/138876745-6a6ca704-ce44-4875-8289-2fec1b896d5a.png)
proper date format displayed above

![image](https://user-images.githubusercontent.com/85713568/138876808-58c4cc2e-0f82-48d5-8e32-fdb11bd3425b.png)
improper date format above

![image](https://user-images.githubusercontent.com/85713568/138876976-2bc7dc6b-a7bb-4a58-9510-a242524e7386.png)
![image](https://user-images.githubusercontent.com/85713568/138877026-ad22c1e8-4a4d-40cf-90a1-be4854cb4d21.png)

Searches are case sensitive

![image](https://user-images.githubusercontent.com/85713568/138877184-0072a60c-5950-4b7f-874e-99478b2b1596.png)

Multiple filters can be used at the same time


### Summary
In summary this webpage does provide an easy access to this dynamic table and is fairly easy to navigatre but the page does contain flaws. 
The filter's are very specific and a regular user may not be aware of the case sensitivity and date formatting, an adjustment to this would be allowing broader user inputs and having the code filter it into a searchable string within the data.
A filter suggestion could also show up providing all the possible filters within each filter section.
