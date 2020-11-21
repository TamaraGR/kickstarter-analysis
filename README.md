# Kickstarter Campaigns Analysis Based On Launch Dates and Goals

## Overview of Project

This is an analysis of the [Kickstarter Challenge database] (https://github.com/TamaraGR/kickstarter-analysis) files. In this analysis we are looking at the Theater kickstarter campaigns outcomes sorted by their launch date and plays kickstarter campaigns based on the goals for fundraising. 
We are looking to estabish trends regarding when it is best to start a fundraising campaign, and what goal amount is most ideal for the campaign to be successful. 

### Purpose

This analysis is performed with the purpose of comparing different theater/ plays-related [Kickstarter campaigns] (https://www.kickstarter.com/) in relation to their launch dates and their funding goals.  

## Analysis and Challenges

*Below is the analysis of how various Kickstarter campaigns for theater/ plays have scored in relation to their launch dates and their funding goals.*

### Analysis of Outcomes Based on Launch Date

This part of the analysis is based on the **Theater Outcomes by Launch Date** tab on the [Kickstarter Challenge database] (https://github.com/TamaraGR/kickstarter-analysis/blob/main/Kickstarter_Challenge.zip) file. 
In this part of analysis we are looking at **Successful**, **Failed** and **Canceled** theater Kickstarted campaigns between the years of 2010-2017 (up to 3/15/2017). We are looking 
at a total of 1369 campaigns, including 839 successful, 493 failed and 37 canceled. 

As you can see from the [Theater_Outcomes_vs_Launch] (https://github.com/TamaraGR/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png) pivot chart image, 
the successful campaigns **peak** during the month of **May** at 111 and are at their **lowest** in the month of **December** at 37. The failed campaigns have a much narrower range. 
They also **peak** during the month of **May** at 52 and are at their **lowest* during the month of **November** at 31. The canceled campaigns range between 0 to 7 in a said month, 
with **highest** number of cancellations in **January** and **lowest** in **October**. Overall, according to the analyzed database, the Kickstarter platform saw less activity in the end and the beginning
of the year, while it saw peak of activity during the month of May. 

### Analysis of Outcomes Based on Goals

This part of analysis is based on the **Outcomes Based On Goals** tab on the [Kickstarter Challenge database] (https://github.com/TamaraGR/kickstarter-analysis/blob/main/Kickstarter_Challenge.zip) file.
In this part of the analysis we are looking at the percentages of **Successful**, **Failed** and **Canceled** campaigns, depending on their fundraising goals. The fundraising goals ranges that we are looking at are 
less than 1000, 1000 to 4999, 5000 to 9999, 10000 to 14999, 15000 to 19999, 20000 to 24999, 25000 to 29999, 30000 to 34999, 35000 to 39999, 40000 to 44999, 45000 to 49999 and greater than 50000.

If you refer to the [Outcomes_vs_Goals] (https://github.com/TamaraGR/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)pivot chart image, you will see that the highest percentage (76% and 73%) of successful fundraisers for plays on Kickstarter  are for the amounts  under 1000 and between 1000 and 4999.  
There are no cancelled plays for these amounts (there are no cancelled plays under the given above criteria in general), and therefore the lowest percentage of cancelled fundraisers (24% and 27% is for the amounts ounder 1000 and between 1000 and 4999. 

The numbers of campaigns on the lower monetary value side is in general much higher than the number of campaigns with higher monetary value. For example, a total of 186 campaigns were started for the amounts under 1000, a total of 534 campaigns were started 
for the amounts between 1000 and 4999. Meanwhile, only 3 campaigns were started for the amount of 40000 to 44999, 1 campaign for the amount of 44999 to 49999 and only 12 campaigns for the amount above 50000. 

The success and failure percentage is equally distributed for the amounts of 15000 to 19999. And the campaigns for the higher amounts have much lower success rate: 0% for 45000 to 49000 and 17% for above 50000. 
The success rate rises to 67% for the amounts of 35000 to 39999 and 40000 to 44999. 

### Challenges and Difficulties Encountered

The main challenges and difficulties encountered during this analysis are related to this data being limited (small range of variables at certain points, which doesn't allow complete certainty of assumptions and conclusions) and not up to date data (it ends in 2017). 

## Results

*In the paragraph below we are looking at the conclusions of the Kickstarter campaigns analysis. 

**- What are two conclusions you can draw about the Outcomes based on Launch Date?**

The first conclusion is that end of the year and beginning of the year are not the best time for launching a kickstarter campaign, because the probability of being successful is much lower, judging from the statistics that we are presented with. 

The second conclusion is that the best time for launching a Kickstarter fundraiser is around May, because this is when the probability of being successful is much higher. 

**- What can you conclude about the Outcomes based on Goals?**

The lower the goal, the more likely a said fundraiser to be succesful as the percentage of successful campaigns is significantly higher in these cases. 
Judging from the numbers of campaigns in general, more campaigns were started with lower monetary goals than the ones with higher monetary values, which makes the data on the lower monetary value campaigns more reliable (a larger pool of variables to prove the point). 

**- What are some limitations of this dataset?**

The dataset shows data for the years 2010-2017, but we don't have any newer data. Things might have changed in the past 3 years. It must be noted that the past year in particular saw a lot of social issues-based campaigns, including theater/ plays-related fundraising campaigns that 
we can't analyze and take into consideration in this case. Also with the pandemic in 2020 many performance activities are on hold, which must have affected the play/ theater industry and might have affected the fundraising efforts as well, but we can't speculate about it since we don't have the relevant data. 

Also, the way the goals are set, we are missing the number of plays in the Outcomes Based On Golas analysis for funraising efforts looking at 50000 exactly. 
 
Another limitation is that the the higher the values of the fundraising campaigns, the fewer campaigns there were. Which leaves us with a small range of variables for the higher monetary value fundraiser. However, that is also a sign that fewer people are willing to risk their reputation and success rate for higher amount fundraisers. 

**- What are some other possible tables and/or graphs that we could create?**

For the first task, instead of counting the theater fundraisers by month, we could have looked by year to see what year was most successful. We could have also looked at the average length of the campaigns and around what time they ended (versus when they started).
We could have also looked at the percentages of successful versus failed versus cancelled theater fundraisers for the first task. 

For the second second task, it'd be helpful to calculate the percentages of successful  plays' goal amount versus the actually pledged amount.  


