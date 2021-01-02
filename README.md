# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
# **Kickstarting with Excel**

## **Overview of Project**
For this project we had to help Louise analyze the data of crowdfunding. She wanted to know how different campaigns fared in relation to their launch dates and their funding goals. 
We have combed through our data to analyze this funding thoroughly. 
Throughout the data, you will see more added columns for additional analysis such as average of donations etc. Separated the parent category to subcategory showing the true outcome.  Readable date conversions of deadlines and launch dates of each category.
-	Analysis of outcomes of parent category filtering by “theatre” category by their outcomes using Pivot tables and visualized by creating stacked column chart. 
-	Analysis of outcomes of subcategories filtering by “plays” category by their outcomes using Pivot tables and visualized by creating stacked column chart. 
-	Analysis of outcomes based on their Launch date. Filtered “theatre” category by using Pivot tables and visualized by creating line chart. 
-	Louise was inspired by 5 players at Edinburgh Festival Fringe and she wanted to know how they were funded. Using VLOOKUP to find the specific (Edinburgh Research) goals and pledged amounts. 
-	Analysis by country, most successful outcome of the parent and subcategory of theatre and play.  
-	To deepen our analysis for Louise. We used central tendencies to provided unbiased view of the data and make conclusions. This has helped her figure out the outcomes based on the goals and pledged amounts. She can get a clear picture. Also calculated measures of spread including range, variance, standard deviation, and quartiles. 
-	Outlier chart to find out the extreme points of data in our analysis. Louise was interested in GB theater market, especially musicals. We used box plots to show her the amounts of information about a distribution in a small amount of space with her estimated future budget. 
-	Analysing the theatre outcomes vs. launch using Pivot table filtered to “theater” as parent category. 
-	Analysing the outcomes based on goals using goal-based data and “plays”.  

### **Purpose**
The purpose of this project was to help Louise analyse the data of crowdfunding. How different campaigns fared in relation to their launch date and their funding goals in correction with the outcome. 

## **Analysis and Challenges**
Overall analysis was made by combing through the data. The most successful category was theatre/play. We were able to find out peak months in which this category was successful as well. Now we know the goals range of the funding and the most popular month where there will be higher changes of this campaign to be successful. 
There were many challenges throughout the analysis. First, calculating the average and it provided the answer with an error. Using the If function and round function nesting it in helped solved the issue. Second, using the count If function and round function nesting in to provide us the correct answer. 

### **Analysis of Outcomes Based on Launch Date**
To provide the proper analysis to Louise, we provided the theater outcome vs. Launch dates by using Pivot table. Filtered Parent category and years and in correlation to their outcomes only showing “successful”, “failed” and “cancelled”. 
Visualized the relationship, we created a line chart. 
We can see that the highest success of this category was in May. This gives Louise idea as to why this category was most successful and in what month.

[Images to support this Outcome] (resources/ Theater_Outcomes_vs_Launch.png)
 

### **Analysis of Outcomes Based on Goals**
We performed another analysis on outcomes based on goals. In this analysis we used group-based goal amount and used Count If function to populate the outcomes by filtering the outcome column, goal column and choosing subcategory “plays”. Visualized the relationship, we created a line chart. 
Mainly outcomes that were successful in this subcategory was with the goal less than 5000 or between 35000 to 45000. 

[Images to support this Outcome] (resources/ Outcomes_vs_Goals.png)


### **Challenges and Difficulties Encountered**
The main challenge was to calculate the outcome based on goal based. The Count If function. The only mistake I was making is in criteria section, instead of plays, I was typing play which was giving me an error. After careful analysis of the formula, I had corrected my mistake. A single letter mistake can skew your data.  


## **Results**

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Successful theater outcome was the highest in the month of May. 
2. Louise should keep this campaign because it provided the highest successful funding results and in the month of May. 

- What can you conclude about the Outcomes based on Goals?
1. The outcome based on goal, the percentage successful and percentage failed was positively correlated with each other since there was no cancellations in this category.
2. Outcomes were successful in this subcategory was with the funding goal less than 5000 or between 35000 to 45000. 


- What are some limitations of this dataset?
Limitations in this dataset: 
Dates were in the form of Unix Timestamps. Had to convert it into readable data. 
When calculating the average, it would not allow to calculate it easily. 

- What are some other possible tables and/or graphs that we could create?
We could use bar chart/column chart instead of line chart for visualization. More use of If function instead of using conditional formatting. 
