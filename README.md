# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project is to take existing data relating to past and active Kickstarter projects, analyze it using basic Excel functions, and present it in a visually effective manner that communicates results.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The analysis of outcomes based on launch date shows absolute number of successful, failed, and canceled projects as a function of calendar month.  However, no consideration is given to which year data is from; it is assumed there is no trend and all years are weighted equally.
![Theatre_Outcomes_vs_Launch](https://user-images.githubusercontent.com/107806410/177900718-45f49fab-f787-481a-b05d-92478255c155.png)

### Analysis of Outcomes Based on Goals
The analysis of outcomes based on goals converts successful, failed, and canceled projects into a percentage of the total, and is a function of overall project size (as measured by dollars) rather than by calendar month.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/107806410/177900732-23a13744-d7cd-4136-9056-8b24891c3674.png)

### Challenges and Difficulties Encountered
One challenge experienced with the outcomes based on goals worksheet was that the formulas were not easily transferable via copy and paste, and therefore formulas had to be entered manually in each cell (for the first the columns).  This is an inefficient but ultimately effective method of entering formulas.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1:  The number of canceled projects are relatively low compared to the number of successful and failed outcomes, and are fairly steady throughout the year.
2:  The number of successful projects peaks in May, then drops off fairly steadily for the rest of the calendar year. 

- What can you conclude about the Outcomes based on Goals?
There are no canceled projects that fall under the category of plays.

- What are some limitations of this dataset?
One main limitation of this dataset is that each project is unique and is therefore qualitative data.  This necessitates grouping projects that can have dissimilar characteristics into categories in order to do quantitative analysis.  This can give a good overall picture but is not necessarily 100% accurate.

- What are some other possible tables and/or graphs that we could create?
We could create time series data that looks at trends over time rather than just calendar month.
We could see if geographic location has any causal relationship to outcome.
We could look at percentage success rates as a function of category (both parent and sub).
