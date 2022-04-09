#Overview of Project

Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset that we’ve already combed through, we’ll visualize campaign outcomes based on their launch dates and their funding goals to see how her play compared to others.

#Analysis and Challenges:

We created two graphs to be able to help us understand the relations between launch date and funding goals.
- The first one was targeted for the Theater category. We created a line graph divided up by months for plot points to see if there was a correlation with the date and timing itself. 
- ![Theater_Outcomes_vs_Launch.png](kickstarter-analysis/Resources/Theater_Outcomes_vs_Launch.png)
- We made this through utilizing a pivot table. A challenge we found was trying to separate the data to get to months by grouping them up. 

The second graph was more refinde towards plays and their success/fail/cancel rate. 
- ![Outcomes Based on Launch Date](kickstarter-analysis/Resources/Outcomes Based on Launch Date.png)
- We used codes like =countifs() and =sum() to be able to create the graph. One challenge was trying to find a more efficient way to copy and paste the countifs code over to each column of successful, failure, and canceled.
 
#Results:

1. Looking at the data we saw that towards spring/summer there was a rise in successful theaters that were opened while as it headed towards winter, success rate dropped as well as the rate of theaters opening. In terms of failures, the number of theatres that failed stayed around the same number year round. 
2. In regards to plays, we noticed that no plays were ever canceled. Plays that did well were the ones that had a lower goal to strive for.
3. Things we could improve/limits of this analysis is that we never dived deeper into the data set. We didn't know what types of plays were successful, the genre, and also how long they had to be able to reach/kickstart to their goal. These factors could be expanded upon with more charts and graphs to better analyize the data we were given.
