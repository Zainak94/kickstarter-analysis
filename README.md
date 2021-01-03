# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
# **Kickstarting with Excel**

## **Overview of Project**
For this project we had to help Louise analyze the data of crowdfunding. She wanted to know how different campaigns fared in relation to their launch dates and their funding goals. 
We have combed through our data to analyze this funding thoroughly. 
Throughout the data, you will see more added columns for additional analysis such as average of donations etc. Separated the parent category to subcategory showing the true outcome.  Readable date conversions of deadlines and launch dates of each category.
- I performed an analysis of outcomes of parent category. Filtering the data by “theatre” category and in relation with their outcomes,"successful", "failed", "cancelled" using Pivot tables and visualized by creating stacked column chart. 
- To get deeper into the analysis, I performed an analysis of outcomes of subcategories. Filtering the data by “plays” category and in relation with their outcomes,"successful", "failed", "cancelled" using Pivot tables and visualized by creating stacked column chart. 
-	We needed to know how these outcomes perform in relation to their launch date. I performed an analysis of outcomes based on their Launch date. Filtered the data by "theatre" category and outcomes in relation with their launch dates. Arranged the launch dates by months using Pivot tables and visualized by creating line chart to show the trend.     
-	After finding out the most successful campaign, we did the analysis of campaign outcome based on their launch dates and their funding goals. Analysing the theatre outcomes vs. launch using Pivot table filtered to “theater” as parent category in relation with their outcomes. 
-	Lastly, performed an analysis using the Count If function to find out the number of "successful","failed" and "cancelled" outcomes based on goals using goal-based data and setting the criteria to subcategory of “plays". Used the Sum function to find out the total number of projects and in relation with thier individual percent.   

### **Purpose**
The purpose of this project was to help Louise analyse the data of crowdfunding. How different campaigns fared in relation to their launch date and their funding goals in relation with their outcome. 

## **Analysis and Challenges**
Overall analysis was made by combing through the data. The most successful category was theatre/play. We were able to find out peak months in which this category was successful as well. Now we know the goals range of the funding and the most popular month where there will be higher changes of this campaign to be successful. 
There were many challenges throughout the analysis. First, calculating the average and it provided the answer with an error. Using the If function and round function nesting it in helped solved the issue. Second, using the count If function and round function nesting in to provide us the correct answer. 

### **Analysis of Outcomes Based on Launch Date**
To provide the proper analysis to Louise, we provided the theater outcome vs. Launch dates by using Pivot table. Filtered Parent category by "theatre" and years and in correlation to their outcomes only showing “successful”, “failed” and “cancelled”. 
Visualized the relationship, we created a line chart to show the trend by every month.
We can see that the highest success of this category was in May. This gives Louise idea as to why this category was most successful and in what month.

![Theater_Outcomes_vs_Launch](https://github.com/Zainak94/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)
 

### **Analysis of Outcomes Based on Goals**
Louise knew that the category was most successful in May. We performed another analysis on outcomes based on goals. In this analysis we used group-based goal amount of funding and used Count If function to provide us number of successful, failed and cancelled outcomes. Then used the Sum function to provide the total number of projects to find out the percentage of outcomes. Visualized the relationship, we created a line chart. 
Mainly outcomes that were successful in this subcategory was with the goal less than 5000 or between 35000 to 45000. Now Loiuse knows the goal funding amount that made this category successful. 

![Outcomes_vs_Goals](https://github.com/Zainak94/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)


### **Challenges and Difficulties Encountered**
The main challenge was to calculate the outcome based on goal based. The Count If function. The only mistake I was making is in criteria section, instead of plays, I was typing play which was giving me an error. After careful analysis of the formula, I had corrected my mistake. A single letter mistake can skew your data.  


## **Results**

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Successful theater outcome was the highest in the month of May. 
2. Louise should keep this campaign because it provided the highest successful funding results and launch it in the month of May. 

- What can you conclude about the Outcomes based on Goals?
1. The outcome based on goal, the percentage successful and percentage failed was positively correlated with each other since there was no cancellations in this category.
2. Outcomes were successful in this subcategory was with the funding goal less than 5000 or between 35000 to 45000. Louise has an idea as to what the funding goal amount should look like in order for this campaign to be successful. 


- What are some limitations of this dataset?
Limitations in this dataset: 
Dates were in the form of Unix Timestamps. Had to convert it into readable data. 
When calculating the average, it would not allow to calculate it easily. 

- What are some other possible tables and/or graphs that we could create?
We could use bar chart/column chart instead of line chart for visualization to show the trends. We can use If function to find out the results of the outcomes. 
