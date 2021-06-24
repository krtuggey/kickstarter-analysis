# Kickstarting with Excel

## Overview of Project
This project is a continuation of Module 1's analysis for Louise's kickstarter that focused on the theatre subcategory of kickstarters, launch dates, and fundraising goals.

### Purpose
This project is designed to use the previous analysis and data compiled for Louise's initial fundraising goals. Now that her play has gained pledges close to her fundraising goal,she is now interested in another data analysis focused on the relationship between other campaign's launch dates and their funding goals. This analysis project will provide the analysis and visualizations for Louise's understanding. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To analyze the data of the outcomes in the frame of the campaign's launch date, first a pivot table was created for the theater category. This table displayed the values of
the outcomes based on the year and month each campaign was launched. Next, a line graph was created from this data for an easier-to-read visualization. Based off of the
analysis conducted, the majority of successful theater campaigns are launched in the summer, around May to June, then the success rate steadily declines. October has the largest
amount of failed campaigns.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/84139177/123313612-4c75e880-d4ef-11eb-8658-c67ec3f6ffea.png)

### Analysis of Outcomes Based on Goals
Data analysis with the COUNTIFS and SUM formulas provided the number of the successful, filed, and canceled based off of goal ranges. 
The largest amount of both successful campaigns and failed campaigns, as well as total campaigns were found in the  
$1000 to $4999 range. There were no canceled projects in the "plays" subcategory. Very few projects set goals in the $40000 to 49999" range.
Additional calculations and a visual chart were added to this analysis to show the percentage of successful and failed campaigns. Here there is a clearer pattern: the highest percentage of succesfful campaigns are in the $0 to $4999 range while the highest percentage of failed campaigns are in the $45000 and above range.

![Outcomes Based on Goals Sheet](https://user-images.githubusercontent.com/84139177/123313663-57c91400-d4ef-11eb-9eb0-fe9218f9c01e.png)
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/84139177/123313703-61527c00-d4ef-11eb-8135-351a31be37b7.png)

### Challenges and Difficulties Encountered
I had some difficulty with the COUNTIFS, first while I practiced understanding the formula, and later as I inputted the formula into different cells. The process was
a bit meticulous (perhaps there are easier ways to handle inputting a formula over and over again) and I worried about human error. I was careful to check my work, so 
hopefully my work turned out correct.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	The first conclusion that I came to are that May to June are likely the best time to launch a campaign. Secondly, because of October's amount of failed campaigns, 
	I would not recommend a campaign launch during that month.

- What can you conclude about the Outcomes based on Goals?
	To have a successful campaign it would be smart to keep the campaign's goal near a smaller range of money, like $5000 or less. It would be unwise to set a high
	goal for your campaign ($45k or more) based off of the percentages of failed campaigns.

- What are some limitations of this dataset?
	This dataset could include some errors based on Kickstarter's data. For example, there might be human error/input errors that provide incorrect information. Also, the
  Kickstarter database may not be up to date, causing us to deal with dated information. Also, I'd be curious to know how many kickstarters delete their campaign profile once
  they are successful or failed because that could be a limitation to the dataset as well.

- What are some other possible tables and/or graphs that we could create?
	We could delve into the descriptions of theatre and plays to create a sub-subcategory of genres and create tables of the outcomes based on genres. It might give us helpful  
  insight based off of the genre of the client's play (perhaps it's a comedy) and compare that to how other comedies (instead of dramas, horror, etc.) faired.

