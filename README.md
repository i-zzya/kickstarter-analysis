# KickStarter Outcomes
## Project Rundown
In a previous analysis we helped Louise determine if Theater campaigns were successful enough for her to launch a project. Our findings determined Theater campaigns were successful and this led Louise to make an informed decision about her personal project "Fever". She came close to her funding goal in a short amount of time and now wanted to know of launch date vs. funding goals outcomes. 

## Analysis and Challenges

### Theater Outcomes by Launch Date
In order to find the outcomes by launch date we created a pivot table and filtered our dataset by "Parent Category" and "Years". We then selected "Theater" as the only category we are analyzing data for sorted the outcomes in descending order. Finally, to present our data we used a line chart (with markers) to show the relationship between succesful, failed, canceled campaigns and their launch dates. 


![pivottable mod1](https://user-images.githubusercontent.com/99618784/156447999-99caf4b5-4e2c-42d3-b60f-5b12bdefa4c7.png)
![Theater_Outcomes_vs_Launch-2](https://user-images.githubusercontent.com/99618784/156448001-29589d2b-54d4-494b-b2f2-fd83231e488c.png)

### Outcomes Based on Goal
Using Excel functions we were able to create formulas to get percentages for successful, failed, and canceled plays based on the amount of the funding goal. With the number of outcomes as our headers and goal amount as our rows, we used the following formuals: 

Number Successful: 

=COUNTIFS(Kickstarter!$F:$F,"successful",Kickstarter!$D:$D,"<1000",Kickstarter!$R:$R,"plays")

Number Failed: 

=COUNTIFS(Kickstarter!$F:$F,"failed",Kickstarter!$D:$D,"<1000",Kickstarter!$R:$R,"plays")

Number Canceled:

=COUNTIFS(Kickstarter!$F:$F,"canceled",Kickstarter!$D:$D,"<1000",Kickstarter!$R:$R,"plays")

Again we used a line chart to best visualize our findings. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/99618784/155897477-f837b590-52bc-4504-a518-05b5fbb00880.png)

### Challenges
My only challenge was figuring out the correct formula in Excel to output the percentages. Having the proper placement or right characters and not get an error code was time consuming but practice makes perfect. 

## Results

After looking over our cleaned data we have come to the conclusion that the best time to launch a "Theater" campagin is May followed by June. With that being said, May also has the highest failed launch date for the campagin overall. The Summer season (May through August) has the most failed campagins followed by a spike in October. Timing the launch of a campagin isnt the only factor to having a successful project. If the goal amount is below $5000, it has a success rate of over 70%. Goal amounts between $5000 and $25000 have about a 50/50 chance of failing or succeeding. I feel there is limited data for financial goals of $25000 and higher to determine a valid success or failed rate compared to the number of projects with smaller goals. We have over a 1000 campagins to review from with goals under $25k and under 50 with goals over. This data set is also 5 years old and trends change. There could be double the amount of people trying to launch a theater campagin and investors may want to support other types of projects. We could create another pivot table to find the amount of successful/failed/canceled subcategories (i.e plays, musicals) to see if one is more popular than the other. Breaking down what subcategory has had the most success over the years, finding the trend, could help others make the best decision when it comes to launching their own campaign. 








# Analysis Preformed on Kickstarter Data Set


While analyzing over thousands of different kickstarter projects, our primary focus was to determine the success rate of Theater Campaigns.After cleaning our data set, we learned that of the 912 Theater campaigns in the U.S-512 were successful. It is also important to note that majority of successful campaigns were run in May and June.

![Parent Category Outcomes-1](https://user-images.githubusercontent.com/99618784/155526405-7ddabb86-a834-455a-aa4f-b77783f16b8f.png)


![outcomes based on launch-1](https://user-images.githubusercontent.com/99618784/155626479-36a4e101-bfbe-4936-b279-d4e2f89b5b7d.png)

Based on our findings Louise is likely to run a successful Theater Campaign kicking it off at the beginning of summer. 



