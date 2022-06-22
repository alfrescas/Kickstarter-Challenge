# Module 1 Kickstarter-Challenge 

## Overview of Project

Performing an analysis to uncover trends, for Louise after her play _Fever_ came close to its fundraising goal. 
Louise would like to know how different campaigns performed with their launch dates and goals . The visual data that will be shown in the following, is the trends and outcomes based on launch dates and their goals. To give Louise an understanding on the information she requested.

## Analysis 

#### Outcomes Based on Launch Dates:

  In the graph below,it shows us data about theaters outcome based on launch dates. In order to obtain this information, I used the timestamps provided in the kickstarter data sheet, in the launch date column, and converted it into a readable format. After that, I was able to calculate the number of success, failed, and canceled outcomes based on their launch dates, as shown below.
  
  
<img width="269" alt="image" src="https://user-images.githubusercontent.com/107371010/175130154-7e011c68-617d-499e-87d1-3d5e7e6d2708.png">
  
  
  
 In the line graph below, _Theater Outcomes by Launch Date_, it appears that the months of May and June have the most success rate, with May being the leading month with 111 successful theater launches, the following month being June, which comes in second with 100 successful launch dates.  


![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/107371010/175114708-8e707eda-2a0c-4c85-89eb-71c5fa4bb518.png)



#### Outcomes Based on Goals:

Starting from a dollar-amount range of $1,000 to $50,000 or more. Then separating that range into internvals of $5,000. As shown below.


<img width="411" alt="image" src="https://user-images.githubusercontent.com/107371010/175127669-e93501d1-077e-4f34-9207-87251742255b.png">


 I then used the COUNTIFS() functions to populate the number of successful, failed, and canceled by filtering "outcome" and "goal" on the Kickstarter sheet. I also filtered the "Subcategory" column and "plays" for the last criteria. After inputting all that information, I calculated the percentage of successful, failed, and canceled projects.

The goals that were met with more success are $1000 campaign goals with a success rate of 76%. The next goal is between $1000 to $4999, these goals were met with a 73% success rate. 


![Outcomes_vs_Goals](https://user-images.githubusercontent.com/107371010/175114875-e4c2b2ee-1a6d-4e93-bd69-600beba9f1a2.png)



## Challenges:

Some of the challenges I encountered when doing this analysis, is that I didn't anticipate the amount of time I would be stuck trying to figure how to adjust the data on the Outcomes Based by Goals. There was some confusion on why my line graph didn't show the way it was meant to, but as I was looking into my dollar amount ranges in the row column; I realized they were not descending. I had to manually drag the amounts into the correct cell. After doing this, my line graph turned out perfect.


## Results

##### Outcomes by Launch Date:

- Theater Outcomes by Launch Date, based on the data analysis, the months that had a peak their theater success rate are May and June. After those months there is a significant decrease leading to the month of October, where it picks up a little, then picks up again in Febuary. 
- It would be wise to prepare for a theater launch earlier in the beginning of the year, in order to have better success when the months of May and June come around.

##### Outcomes Based on Goals:
- There is a higher percentage in success rate when the dollar-amount goals are to $1,000 or from $1,000 to $5,0000. The dollar-amount ranges that start from $25,000 to $50,000 or more, are met with a higher percentage of failing. There is a better chance to be success in funding for campaign goals when the dollar-amount range is up to $1,000. 

##### Limitations of the Dataset and Recommendations:
The data didn't go into more depth on why the some theater productions outcomes were better than others, it would provide a better understanding on how to create more successful theater outcomes. I would recommend adding more bar graphs, it is beneficial to have another visual aid that shows the data in a different way. 
