# KickStart-My-Chart

## Background 
Over two billion dollars have been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the over 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Since getting funded on Kickstarter requires meeting or exceeding the project's initial goal, many organizations spend months looking through past projects in an attempt to discover some trick to finding success. For this week's homework, you will organize and analyze a database of four thousand past projects in order to uncover any hidden trends.

## Technology

Excel was used to modify and analyze the data of four thousand past Kickstarter projects in an attempt to uncover some of the market trends.

## Conclusions

1. Campaign with Music category are most likely to become successful. It if followed by theatre. Games and food categories are the most likely to fail. 

![Bar graph: Success based on Category](https://github.com/mddesta/KickStart-My-Chart/blob/master/Images/Category.PNG)
    
2. Documentary, classical music, electronic music, hardware, non-fiction, pop, radio &podcast, rock, shorts, table top games, and television subcategories have a 100% track record of success. 

![Bar graph: Success based on Sub-category](https://github.com/mddesta/KickStart-My-Chart/blob/master/Images/Sub-category.PNG)
    
 3. There are less projects created in December and the probability of success decreases as compared to other times of the year. 

![Bar graph: Success based on Date](https://github.com/mddesta/KickStart-My-Chart/blob/master/Images/Date.PNG)

## Limitations

The dataset does not include any information about the creators of the Kickstarter. The lack of this information will prevent us from painting a full picture regarding why the projects were successful. For example, a famous person will have a higher chance of success and that would be overlooked by the data presented. In addition, the dataset does not mention the number of people who looked at each campaign. This will give us which ones were truly appealing to the public based on the percentage of people who looked at the campaign and contributed. 
    
## Considerations

*	Plotting goal amount with pledged amount will give insight to whether the amount of money needed has impact on gaining funding. 

*	An anlysis to show the number of projects in canceled, failed, like and successful status per country would help us determine if the location of the project has impact on the success of the project. 
## Reading guide for StarterBook.xlsx: 

#### In Sheet1:

1. Each cell in the state column with a different color, depending on whether the associated campaign was "successful," "failed," "cancelled," or is currently "live". Green represents "successful", red represents "failed", blue represents "cancelled" and yellow represents "live."
2. Cells in the percent funded column using a three-color scale. The scale starts at percent funded equals to 0 and gets darker shade of red when percent funded gets larger, transitions to green at percent funded equals to 100, and then moves towards to blue at percent funded equals to 200.
3. Category column at Q and sub-category column at R, are splited from the Category and Sub-Category column at N.

#### In Sheet2:

1. A pivot table that can be filtered by country, counts how many campaigns were "successful," "failed," "cancelled," or are currently "live" per category.
2. A bar chart is generated based on the pivot table. 

#### In Sheet3:

1. A pivot table that can be filtered by country and category, counts how many campaigns were "successful," "failed," "cancelled," or are currently "live" per sub-category.
2. A bar chart is generated based on the pivot table. 

#### In Sheet4:

1. A pivot table that can be filtered by category and Years, counts how many campaigns were "successful," "failed," "cancelled," or are currently "live" per month.
2. A line graph is generated based on the pivot table. 

#### In Sheet5:

1. Number Successful, Number Failed, and Number Canceled columns are calculated with COUNTIFS() regarding ranges. 
2. A line chart which graphs the relationship between a goal's amount and its chances at success, failure, or cancellation.
