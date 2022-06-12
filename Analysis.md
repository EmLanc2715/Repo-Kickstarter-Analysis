# Kickstarting with Excel

## Overview of Project
Kickstarter data sourced from a playwrite named Louise was used to analyze production outcomes based on launch date and outcomes based on monetary goals to help make decisions about her own upcoming project.

### Purpose
Louise is interested in how past projects have performed, so she can best prepare herself to produce her own play *Fever*. Louises' play came very close to reaching its fundraising goal, and she wanted to compare different campaigns to better understand which productions were successful and which failed. Specifically, how campaigns progressed in relation to their launch dates and their funding goals were examined. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
First examined were the outcomes of productions based on launch date. Using Louises' Kickstarter data, a pivot table was created that was filtered to only display the outcomes of theater productions. There are three categories used; successful, failed and canceled. A line chart was then created to visaulize the data from the pivot table. ![This is line chart based on the pivot table] ("C:\Users\emili\OneDrive\Desktop\Analysis Projects\Resources\Theater_Outcomes_vs_Launch.png")



### Analysis of Outcomes Based on Goals
I then examined the outcomes of productions based on their fundraising goals. Using the Kickstarter data, a worksheet was created to calculate the number of successful, failed, and canceled projects relative to their fundraising goals. The fundraising goals were broken down into ranges consisting of less than $1,000, $1,000 to $4,999, $5,000 to $9,999, and so on, up until over $50,000. After calculating the total number of projects that failed, succeeded or were canceled in the differing goal ranges, the perecentages of each were then found. ![This is a line chart created to visualize the data from the new worksheet] ("C:\Users\emili\OneDrive\Desktop\Analysis Projects\Resources\Outcomes_vs_Goals.png")

### Challenges and Difficulties Encountered
I did have challenges when working on the Outcomes Based on Goal worksheet. I found the COUNTIFs formula difficult to understand at first, especially with the different goal ranges that had to be worked into the formula. After researching the best way to add the ranges so that excel could extract the correct info, I copy and pasted the formula that worked for me. I then pasted and revised the formula to fit parameters of the cell I was working on. I had to change, specifically the monetary ranges and the label of successful, failed and canceled.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. For every month examined there were always more successful productions than failed and canceled combined, besides December. This illustrates that most outcomes were successul.
    2. April through August had the most launch dates and the most successful launch dates. One could conclude that between April and August would be the best time to launch a production.

- What can you conclude about the Outcomes based on Goals?
    The highest percentage of successful productions had goals between less than $1,000, $10,000 to $14,999 and $35,000 to $44,999. The highest percentage of failed productions had goals between $20,000 to $34,000, and the peak of failed productions had a goal of $45,000 and more. 

    As illustarted by the line chart, the highest percentage of successful productions had goals of less than $1,ooo. The highest percentage of failed productions had goals of $45,000 or more.

- What are some limitations of this dataset?
    Limitations of this datset are that for both of the different worksheets and graphs, different categories were being examined. In the Outcomes based on goal dataset, only plays were being examined. In the Theater Outcomes by Launch Date dataset, only theater productions are being examined. These two categories overlap, but there are mulitple different theater productions, plays are only one type. When looking at the data and comparing the graphs, it is important to keep in mind that the data sets are not the same, even though they are grouped together in this project. 

    Another limitation would be the source of the information. Louise created the Kickstarter worksheet herself. To my knowledge there are no descriptions of where her data was sourced.

- What are some other possible tables and/or graphs that we could create?
    A possible table/graph that could be created to help best inform Louise of how to produce and launch her play would be a graph showing the relationship between how much money was pledged in regards to the goal and outcome of the productions (plays).
    Another interesting graph/table that could be created could show the number of backers for plays in relation to the pledged amount.
