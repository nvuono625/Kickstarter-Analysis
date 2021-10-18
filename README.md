# Kickstarting with Excel

## Overview of Project
Kickstarter is a project that examines crowdfunding of different creative projects to identify trends of campaigns from 2009 through 2017. 

### Purpose
The purpose of this project is to dissect and analyze raw data pertaining to campaign history and format the data into interactive visualizations that can be depicted to review successful, live, failed, or canceled campaigns, campaigns based on region, fully funded and not fully funded campaign, etc.

## Analysis and Challenges
The initial challenge of this dataset was to make sure it was organized to be formattable. The “category and subcategory” column needed to be separated into their own columns so that the analysis could be more detailed. 

### Analysis of Outcomes Based on Launch Date
In this analysis, the data was categorized to depict theater outcomes based on launch date. The first step was creating a “years” column. Step two was creating the pivot table and setting the fields. “Parent Category” and “Years” were set as filters, “Date Created Conversion” as rows, and “Outcomes” as columns and values. Next was filtering the parent category to only “theater”, removing “live” campaigns, and making the rows show months. This pivot table was then generated into a line chart showing the theater outcomes (successful, failed, and canceled) month to month.
![Resources/Theater_Outcome_vs_Launch](/Resources/Theater_Outcome_vs_Launch.png)

### Analysis of Outcomes Based on Goals
In this analysis, the outcomes of plays based on funding goal amount was transcribed into a percentage and made into a line chart comparing three different outcomes; successful, failed, and canceled. The data had to be charted; Columns were grouped by number of successful, failed, and canceled, and the percent of each outcome. Twelve rows broke each column down into increments of $5000 up to greater than $50,000. The COUNTIFS function was then used to fill the columns that determined the number of outcomes per each $5000. Percentages were then calculated into their own respective column. Now to visualize this data, a line chart was generated.
![Resources/Outcomes_vs_Goals](/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
The challenges and difficulties encountered was being able to create more columns of data to further break down the analysis of each campaign. The more we break down and categorize data, the more ways we can analyze and create visualizations that express data into a readable format
Qqq	`. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
![image](https://user-images.githubusercontent.com/91674541/137666428-f57bd20a-d93e-41bd-8dd1-0f27157f113c.png)
