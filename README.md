# Kickstarting with Excel

## Overview of Project
The goal of this analysis was to uncover any trends over the course of an eight-year data collection of Louise Kickstarter campaign. The data collected covered a range of information that looks overwhelming. We were able to breakdown the data in order to highlight trends that were hidden within the Kickstarter data set. 

### Purpose
The purpose of this project was to help Louise make sense of the data she has compiled over the course of eight years. By breaking down the information we were able to highlight outcomes that were successful, failed, canceled or live. From there we could show how those outcomes could be affected based on launch date and their goals.


## Analysis and Challenges
Two areas of focus that were taken on this analysis were Outcomes Based on Launch Date and Outcomes Based on Goals. We completed two analyses to understand the data better. The first showed a monthly trend of the data based on launch date for the outcome status for theaters. The second broke down outcomes based on the initial goal dollars for the plays.


### Analysis of Outcomes Based on Launch Date 
When analyzing theater campaigns based on their launch date, the data shows that there are more campaigns between May and July and that they are more likely to be successful. If we look at Figure 1 (Theater Outcomes Based on Launch Date) there is a large spike from the successful campaigns starting in May that drops in September. From this information we can indicate that more Kickstarter campaigns launch in warmer months and those campaigns see success.  In Figure 1 the line graph shows a dip in successful campaigns when launch dates start in November. If we look at failed campaigns, there are no significant months where failed campaigns increase. It appears that more successful campaigns launch in summer months.  

### Figure 1
![Theater Outcomes Based on Launch Date](https://user-images.githubusercontent.com/99099706/156939899-7435c7db-905d-435b-9cc2-60c44571ae1f.png)

### Analysis of Outcomes Based on Goals
Another form of analysis taken was by compiling the Kickstarter campaign goals and separating them starting at less than $1,000 and increase them by $4,999 at a time, finishing at $50,000 or more. By compiling this information, the data shows the percentage of successful goals and percentage of failed goals. Canceled goals were also included in the analysis, but there were no canceled plays which is why that data doesn’t appear in the graph. Line graph shown in Figure 2 (Outcomes Based on Goal) has the percentage of successful and failed goals on the y-axis and the monetary value on the x-axis. The most successful campaigns had a goal less than $1,000, although overall more campaigns were successful than failed up to $20,000. The graph can be miss leading because of a couple of outliers within the higher donations at $35,000 to $44,999. While 67% are successful, we only have nine projects to analyze. Within the value of $0 to $4,999 we have a total of 720 projects. From this we can analyze that most projects will succeed with a goal less than $20,000. 

### Figure 2
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/99099706/156938543-158fe0dd-0b79-412e-bd32-e4577a2a1952.png)

### Challenges and Difficulties Encountered
One area of difficulty within this analysis was within the Outcomes Based on Goals.  Typing each formula twelve times for all outcomes was going to be very time consuming. Within the formula, the only reference points that would need to change are the goal amount and outcome status. In order to fix this issue, I locked the columns I wanted to reference “D” and “F” with a “$” sign and then I was able to drag and copy the formula. After that, the only part of the formula I needed to update was the outcome status, which I used a find and replace function to quickly update all at once for each outcome. Instead of retyping the entire formula every time I was able to efficiently update my cells using references and the find and replace function.  

## Results
-	In conclusion our analysis shows that more theater campaigns are launched in May through July. While we can see a large spike with successful campaigns in May, the number of failed campaigns is relatively consistent regardless of launch date.   
-	Not only is the launch date a significant factor with success, so are the campaigns goals amount. Campaigns that set their goal between $0 to $4,999 had a 73% success rate. 
-	One limitation of this dataset is that it is only collected for eight years, and we do not have any updated datasets to work with. Our most recent dataset is from 2017, so there could be useful information with a more updated dataset.
-	An additional graph that would be useful to help analyze the Kickstarter Campaigns would be a Box and Whisker Plot. A Box and Whisker Plot would help display the data distribution of the group, if there are any outliers, and if the data is symmetrical. 
