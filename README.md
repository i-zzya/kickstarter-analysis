# KickStarter Outcomes
## Project Rundown
In a previous analysis we helped Louise determine if Theater campaigns were successful enough for her to launch a project. Our findings determined Theater campaigns were successful and this led Louise to make an informed decision about her personal project "Fever". She came close to her funding goal in a short amount of time and now wanted to know of launch date vs. funding goals outcomes.  

## Analysis and Challenges

### Theater Outcomes by Launch Date
In order to find the outcomes by launch date we created a pivot table and filtered our dataset by "Parent Category" and "Years". We then selected "Theater" as the only category we are analyzing data for sorted the outcomes in descending order. Finally, to present our data we used a line chart (with markers) to show the relationship between successful, failed, canceled campaigns and their launch dates. 


![pivottable mod1](https://user-images.githubusercontent.com/99618784/156447999-99caf4b5-4e2c-42d3-b60f-5b12bdefa4c7.png)
![Theater_Outcomes_vs_Launch-2](https://user-images.githubusercontent.com/99618784/156448001-29589d2b-54d4-494b-b2f2-fd83231e488c.png)

### Outcomes Based on Goal
Using Excel functions, we were able to create formulas to get percentages for successful, failed, and canceled plays based on the amount of the funding goal. With the number of outcomes as our headers and goal amount as our rows, we used the following formulas: 

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

After looking over our cleaned data we have concluded that the best time to launch a "Theater" campaign is May, followed by June. With that being said, May also has the highest failed launch date for the campaign overall. The Summer season (May through August) has the most failed campaigns followed by a spike in October. Timing the launch of a campaign isn’t the only factor to having a successful project. If the goal amount is below $5000, it has a success rate of over 70%. Goal amounts between $5000 and $25000 have about a 50/50 chance of failing or succeeding. I feel there is limited data for financial goals of $25000 and higher to determine a valid success or failed rate compared to the number of projects with smaller goals. We have over 1000 campaigns to review from with goals under $25k and under 50 with goals over. This data set is also 5 years old, and trends change. There could be double the amount of people trying to launch a theater campaign and investors may want to support other types of projects. We could create another pivot table to find the number of successful/failed/canceled subcategories (i.e., plays, musicals) to see if one is more popular than the other. Breaking down what subcategory has had the most success over the years, finding the trend, could help others make the best decision when it comes to launching their own campaign. 








# Analysis Preformed on Kickstarter Data Set

## Overview
For this assignment we were asked to analyze thousands of different kickstarter projects. Our primary focus was to determine the success rate of Theater Campaigns for Louise, who is considering launching her own campaign in the U.S. We compared Theater to other parent categories for successful, failed, canceled, and live (dataset from 2017) outcomes.

## Analysis

### Outcomes for Parent Categories
Below you can find a stacked bar graph that shows the outcomes of each "Parent Category". It is fair to say that "Theater" campaigns are very popular and have a high success rate. Of the 912 projects, 525 were met and/or surpassed their goals. 


![Parent Category Outcomes-1](https://user-images.githubusercontent.com/99618784/155526405-7ddabb86-a834-455a-aa4f-b77783f16b8f.png)

### Outcomes Based on Launch

We used a line graph (with markers) to display the outcomes based on launch date. You can see very quickly that May, followed by June and July were the best times to launch a successful campaign. While April and August also have had successful launches, it’s important to note that they have relatively close failed launches as well.

![outcomes based on launch-1](https://user-images.githubusercontent.com/99618784/155626479-36a4e101-bfbe-4936-b279-d4e2f89b5b7d.png)

## Results
According to our findings, Louise is likely to run a successful Theater Campaign if she launches over the summer. We recommend her starting in May however it’s safe to say she will still find success with the genre in the months following. 


