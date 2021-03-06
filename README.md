# Kickstarter Analysis, working with Microsoft Excel

# index
- Purpose
- Analysis and Challenge (a quick look at what this repository will go over)
- Analysis of Outcomes Based on Launch Date
- Analysis of Outcomes Based on Goals
- results and conclusions

# Purpose

Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset that you’ve already combed through, you’ll visualize campaign outcomes based on their launch dates and their funding goals. You’ll then submit a written report based on your analysis and the visualizations you create.

# Analysis and challenge

Here's a quick look at the Kickstarting Analysis and Challenges of this Project, including the following tasks:

* Import data into a table for analysis.
* Apply filters, conditional formatting, and formulas.
* Generate and interpret pivot tables.
* Calculate summary statistics such as measures of central tendency, standard deviation, and variance.
* Characterize data to identify outliers in datasets.
* Perform an Excel analysis with visualizations.
* Interpret common Excel visualizations

# Analysis of Outcomes Based on Launch Date

1. A Years column is created based on the Date Created Conversion column in the Kickstarter spreadsheet.

![image](https://user-images.githubusercontent.com/89880015/148264680-f3777ac8-6b48-4e23-ad00-3fa3b9766c9e.png)

2. A pivot table is created in a new worksheet labeled "Outcomes Based on Launch Date".

![image](https://user-images.githubusercontent.com/89880015/148264849-d1c432e3-f359-41f0-82a7-7af2a862306b.png)

3. The pivot table filters on "Parent Category" and "Years".

![image](https://user-images.githubusercontent.com/89880015/148265015-247d3b0e-9410-45e9-a768-ad6d374c969c.png)

4. The columns, rows, and values in the pivot table fields are correctly populated.

![image](https://user-images.githubusercontent.com/89880015/148265218-6b947111-f0c8-41e2-960e-e7c6998b31ce.png)

5. The "Parent Category" is filtered on "theater".

![image](https://user-images.githubusercontent.com/89880015/148265386-0aaddaf9-1af4-4980-9926-f3d6a4356bea.png)

6. The row labels are changed to display the months of the year, and the campaign outcomes are sorted in descending order.
Grouping data in a PivotTable can help you show a subset of data to analyze. For example, you may want to group an unwieldy list of dates or times (date and time fields in the PivotTable) into quarters and months, etc.

![image](https://user-images.githubusercontent.com/89880015/148265653-cfe7009c-7fc3-486d-a94e-75b8c7b51010.png)

7. A line chart is created showing the number of successful, failed, or canceled projects by month, it has a title, and it is saved as [Theater_Outcomes_vs_Launch.png]

![New_Outcomesbasedonlaunchdate](https://user-images.githubusercontent.com/89880015/133893304-8ad86ae2-0d64-416e-a16e-4870d88c9568.PNG)

# Analysis of Outcomes Based on Goals

1. A new sheet is created with eight columns and twelve rows, according to the instructions.

In the new sheet, create the following columns to hold the data:

* Goal
* Number Successful
* Number Failed
* Number Canceled
* Total Projects
* Percentage Successful
* Percentage Failed
* Percentage Canceled.

![image](https://user-images.githubusercontent.com/89880015/148267948-a0e9d847-8c63-4d4a-b75e-7c20087d15d5.png)

2. The COUNTIFS() function is used to populate the "Number Successful," "Number Failed," and "Number Canceled" columns, based on the project "outcome," the "goal" amount using the goal ranges in Step 3, and the Subcategory "plays".

![image](https://user-images.githubusercontent.com/89880015/148268099-74a12e1b-f653-4769-b27a-06304dcad7b9.png)

3. The SUM() function is used on each row to add the "Number Successful," "Number Failed," and "Number Canceled" columns to populate the "Total Projects" column.

![image](https://user-images.githubusercontent.com/89880015/148268255-f4fe59a4-af65-410b-8bdd-33f025e2580d.png)

4. The percentages of successful, failed, and canceled projects are calculated based on the data from the "Total Projects," "Number Successful," "Number Failed," and "Number Canceled" columns.

![image](https://user-images.githubusercontent.com/89880015/148268366-15894825-6cac-447c-9e07-a24477964541.png)

5. A line chart is created and saved as [Outcomes_vs_Goals.png] with the goal-amount ranges on the x-axis, the percentage of successful, failed, or canceled projects on the y-axis, and an appropriate title.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/89880015/133893238-15198409-d07d-4dd7-a3eb-c671caf047ac.png)
Info on the Final Project: 

## results and conclusions
An Analysis on Kickstarter Campaigns

Performing analysis on Kickstarter to discover trends

* What are two conclusions you can draw about the Outcomes based on Launch Date?

As Conclusions, our Line charts we can see by looking at our data that the months of May and June both have a greater success rate. A bar chart wouldn't be able to convey this information in the same manner.

![Outcomes Based on Launch Date](https://user-images.githubusercontent.com/89880015/132951227-dc5f330a-a0e1-4181-9a54-1d27c5e69d12.PNG)

![ParentCategoryOutcomes(Kickstarter)](https://user-images.githubusercontent.com/89880015/132951236-9e7f9f9f-981d-492f-b90c-e011d4241fae.png)

![Box and Whisker](https://user-images.githubusercontent.com/89880015/132951553-d512f297-3f25-46d4-af4c-447df4972af3.PNG)

![E Research](https://user-images.githubusercontent.com/89880015/132951556-dcef3a55-a2dc-474e-8ad6-06b258ee45d2.PNG)

![Plays_Success](https://user-images.githubusercontent.com/89880015/132951558-4186bbd8-13e0-4702-a230-0bc7b65e284d.PNG)

![Descriptive_Statistics](https://user-images.githubusercontent.com/89880015/132951589-f07951a1-d88f-434d-8f5a-08dde3c4aa48.PNG)

-This project looked into the aspects of Kickstarters, particularly plays within theater. Upon looking at the data my recomendation is that we go forward with the play kickstarter as plays are a very successful within the already very successful theater parent category. There needs to be a lowering of the goal, based on the descriptive statistics. We want to be anywere between $3,000 and $5,000 as our goal. Finally, begining our kickstarter in May or June would be highly advantagous as these months seem to be yeilding the highest success rates. 



![New_Outcomesbasedonlaunchdate](https://user-images.githubusercontent.com/89880015/133893304-8ad86ae2-0d64-416e-a16e-4870d88c9568.PNG)
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/89880015/133893238-15198409-d07d-4dd7-a3eb-c671caf047ac.png)
Info on the Final Project: 



After going through kickstarter data to find what it is that makes kickstarters, particularly plays, successful or unsuccessful.
Now, Loise's play "Fever" came close to its fundraising goal in a short amount of time so now we want to look as and study the 
other kickstarter campaigns and see how they compare based on launch dates and fundraising goals. 

As hinted in the introduction paragraph of this analysis, we are looking to study the success of kickstarter campaigns based on
launch dates and the initial goals that were set, Loise's play came very close to its goal, now we want to understand that 
outcome in the context of the data to see where things may be improved. The analysis was prepared by looking selectively 
at the data that helped make our displays. For the first display we used outcomes based on launch dates. So, we were looking 
to find the success and failures of kickstarters in the theater parent category accross time. Our independent variable in this
case was the month in which the kickstarter was launched and the dependent variable was the success and failure of kickstarters,
canceled kickstarters were also measured. The second display delt with the the outcomes based on goals which had the goals as
the independent variable and the outcome as the dependent variable. In the first display, I encountered no difficulties and
was able to get the task finished in a few minutes. I suppose a dificulty may arise if someone does not know how to use filters
or perhaps cannot put the variables in the right places for the pivot table and subsequent chart. For the second display, I 
actually had an issue. As I was trying to execute the countifs() function, my computer was prioritizing entire spreadsheets 
over the columns I wished to use. So, I was constantly geting 0 as the output. I had to manually go in and rewrite each 
command to get it right. Luckily, after I wrote a few, I was able to copy and past the command and make minimal adjustments 
to get the correct output. 

As for the results, two outcomes can be derived by outcomes based on launch date and one outcoem can be derived from outputes 
based on goals. The outcomes based on launch date is that success rates for theater oarent category go up and peak in may. 
The second outcome is that success begins to fall for the rest of the year. Next, is that generally speaking, success goes 
down when you begin to ask for more money. You generally do better not asking for more then 5000 dollars. 

Now, a summary of the limitations. The most apparent to me involves the second display. There are fewer and fewer trials to 
gather data from as you go up the money asked variable. So, while it may seem intuitive that as you ask for more money, you 
are setting a more difficult bar to climb over, it should be known that a proper conclusion should not be drawn until there
is more data for the parent category. As for the first display, I think that the data is good but I think the display itself
does not capture the whole picture. Rather then time alone affecting the success of plays, I want to see if the general weather
has anything to do with it. Having attended events such as shakespear in the park, I know that such events are carried out in
the summer over other seasons. Nobody wants to sit out in the cold. Perhaps the weather affects people's confidence in
plays as well. I simply believe a better picture can be formed by looking at other varibales that coincide with the month. 
