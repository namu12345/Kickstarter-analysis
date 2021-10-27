# # kickstarter-analysis
Performing analysis on kickstarter data to uncover trends
# # Louise's Crowdfunding Campaign :

Louise has started crowdfunding campaign to fund her first ever play "FEVER" and her estimate to fund this project is over $10000.00.
She is trying to fund her project by starting a campaign and fundraising in different projects.
As per my analysis the highest successful projects were in the month of May-July and then it started falling down.
Also as mentioned earlier campaign had different projects but the most successful as per my analysis is the Theater Category and in that
plays were most successful.I further noticed that the least successful was Food category.


## Purpose of Project:

The purpose of this campaign is to fundraise for her first ever play "Fever" for which she started working on analysing many different campaign projects which were organized in different countries. We'll further see how successful was her campaign and in which country and what month she succeeded the most with the help of charts and graphs.

## Analysis & Challenges :

With the help of Excel functions I started analysing the data for Louise's crowdfunding campaign.
The very first step I did is organize the data so that it can be more easily understood and, therefore, generate insights that will help Louise's project. 
I accomplished this task by sorting filtering and formatting, and by freezing specific columns and rows. the quick view of the same is as below:

![image](https://user-images.githubusercontent.com/92283185/139081280-ccfe8711-fc0c-4dad-80a1-6440011a2b78.png)
In the above image the Deadline and Launched_at columns contain Unix timestamps rather than dates in a standard format and there occured my first challenge for which the timstamp converter tool was provided which helped me to get the dates in standard format.
Further i managed to use the conditional formatting to to automatically apply a preselected color to the cell. So as you can see the outcome column has 4 categories - Successful/Failed/Cancelled/Live where i used conditional formatting color code category to provide Louise the visual presentation of the data in the worksheet with information at a glance.

## Analysis of Outcomes based on Launch date :
The analysis of outcomes based on launch date is better understood by creating Pivot table. The following steps i have to took to create the below Pivot Table 
- Create a pivot table from the KickStarter worksheet, and place the pivot table in a new sheet.
- Label the sheet "Theater Outcomes by Launch Date."
- Filter the pivot table based on "Parent Category" and "Years."
- Place the appropriate pivot table fields in the columns, rows, and values.
- Filter the column labels to show only "successful," "failed," and "canceled."

![image](https://user-images.githubusercontent.com/92283185/139135236-8fd283a0-d473-4e67-bea7-7b0e4a6044b4.png)

The above analysis using Pivot chart explains the theater category was more successful as compared to others and we can have more clear picture by creating a line chart from the pivot table to visualize the relationship between outcomes and launch month. The line chart looks like this :
![image](https://user-images.githubusercontent.com/92283185/139135627-597bf102-381a-4db3-bc6e-b0a5e9822330.png)

### Analysis of Outcomes based on Goals :

![image](https://user-images.githubusercontent.com/92283185/139137209-fcb178a3-88b1-4dfe-90a5-9d39bc2790d5.png)

![image](https://user-images.githubusercontent.com/92283185/139137318-9aa9a62e-b9ca-4bb9-837b-9888aae755e6.png)

### Challenges and Difficulties Encountered

While cretaing Outcome based on Goals it was little challenging for me to get the correct # in "less then 1000" and so on for #successful / failed and all other categories. So when i manually drag all the columns in main kickstarter sheet and when i use the COuNTIF function to calculate the #successful it came both different #'s for me. Then I figured out that even though i am selecting all 1000's in kickstarter sheet in COUNTIF function i cannot mention <= (less then and equal to sign), i only can set up <1000 to get the #'s to match.

## Results
The most successful month were from May-July. 
And the Theater category was more successful as compared to other categories and in theater category the most successful was plays category.
There were 525 successful theater Kickstarters in USA.
And in Great Britain 


- What are two conclusions you can draw about the Outcomes based on Launch Date?
![image](https://user-images.githubusercontent.com/92283185/139140241-b0afafa0-5eaa-475c-8a1c-d53dd77de573.png)

so this Pivot table about Outcome based on Launch date tells us that the most successful month were from May-July then it started falling down. 
And the Theater category was more successful as compared to other categories.

- What can you conclude about the Outcomes based on Goals?
If we filter for only the United States campaigns, we will find that there were 525 successful theater Kickstarters.
We have found that while there are only a total of 604 Kickstarter campaigns for plays in Great Britain, the "theater" category is the most successful.

- What are some limitations of this dataset?
- This dataset doesn't mention anything about individual investors so we cannot figure out our preferred investors.
- This dataset doesn't contain the information about what resources were used to generate this campaign and how much was the expense to manage this huge campaign.
-
- What are some other possible tables and/or graphs that we could create?
- The following are the other possible Pivot charts we could create from this dataset :
- ParentCategory Outcome pivot chart
- <img width="239" alt="Pivot Chart" src="https://user-images.githubusercontent.com/92283185/139141274-4e0dce19-8284-4952-bab4-07d189874c9c.png">

Subcategory Outcome Pivot Chart
<img width="241" alt="Subcategory Pivotchart" src="https://user-images.githubusercontent.com/92283185/139141329-f37729e7-1a59-414c-8d48-b0d51c40466f.png">

Pivot Line chart Datewise
<img width="250" alt="Pivot line chart date wise" src="https://user-images.githubusercontent.com/92283185/139141396-7a29f80f-52e2-47e7-8920-17525a0f7aac.png">





