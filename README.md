# AnalyticsProject
Workspace of my Data and Business analysis projects conducted using a wide variety of tools

## Regional Sales Performance across 3 different data sheets - Tableau

Created this simple project using Tableau where I am analysing the sales performance of a company selling various items distributed across assortments (phones, electronics, etc), Colors, Classficiations (A,B, etc).
This project follows the entire Tableau life cycle, right from importing the data (3 different tables), [blending the data](https://stackoverflow.com/questions/73229666/tableau-what-is-the-different-between-relationship-and-data-blending) creating various sheets, dashboards and finally a story to look at all the crucial information at a glance.

Tableau obviously provides you an opportunity to make interactive dashboards, where you can filter a sheet and see how it impacts the other sheets in the dashboards. A simple example below :

***Story 1***

![1](https://user-images.githubusercontent.com/48427733/212544891-8118ab21-0024-4307-9528-82773f62c305.png)
In the image above, you can see I have used the Geomap as a filter. The Geomap itself gives information on the sales and store velocity (Sales/ number of stores in that state). Store velocity is a better measure of sales performance rather than absolute value.

A KPI board gives key information about sales, stock %, average inventory and more.
Moreover, another dashboard gives sales performance across assortments and classifications in %.

![2](https://user-images.githubusercontent.com/48427733/212544992-77dec5df-90fd-4817-b5a4-76f43b9ceab1.png)

In this second image, we can see that by clicking on a state (South Carolina), we can see the data for only that state. Sales, inventory, stock % and more are updated.

***Story 2***

![4](https://user-images.githubusercontent.com/48427733/212546481-4f31bf01-2c88-4897-bdf6-a832f9960524.png)

In the second dash of the story, we look performance across the time period, in this case on a weekly basis. Top KPI charts give you the sales and inventory while the graph on the top left looks at performance of assortments. Key insights can be drawn in this case, such as the sales of phones has increased in the later weeks. I have added trend lines to point out the future direction of sales, indicating phones to overtake and keep increasing more than the other 2 assortments.

The bottom dashboard is an important one. The Demand Planning Dashboard tells you the sales vs average inventory on hand throughout the weeks. This data can be granulated by adding item IDs, States, classification depending on the use case.

The parabolic shape created in the demand planning dashboard is the forecast of sales and average inventory on hand. Key insights can be the inventory on hand is going to reduce while sales might increase. This can help the managers adapt their planning.

![5](https://user-images.githubusercontent.com/48427733/212545690-5778802d-2f77-4f13-b94a-f3085270b3fb.png)

In this dash, I have added a week slider, where you can check out the performance at a particular week/month. Again, being interactive the dashboard gives you the snapshot of all the graphs at a particular week just by changing the slider.


***Story 3***

![7](https://user-images.githubusercontent.com/48427733/212545903-92f09004-645b-48df-aee5-c92ccea743e2.png)

The last dashboard in my story focuses on each item ID. The top KPI dash gives key information, the bottom left dash, Item performance by Week, gives sales values by classification across the weeks and the final graph is a scatter plot of sales vs average inventory on hand. I have created clusters in this data to better understand the different categories. Items having low sales but high inventory on hand are not good for business and they can be removed, focus should be on items giving high sales and a similar or higher inventory on hand.

I have added a filter for each item. Hence we can look at the performance for an individual item or aggregate multiple items.

![6](https://user-images.githubusercontent.com/48427733/212545928-90d0c8c3-a252-432a-b450-773de80e888f.png)
In the above image, we can notice the number of cluster changes depending on the item. We can conclude the plots in orange color are ideal since they are giving decent sales for the inventory. Red plots indicate really low sales but a high inventory on hand. Such items can be stopped.



## Sales Analysis - Excel and PowerBI

Check out the folder for the detailed report.

<img width="1208" alt="Screenshot 2022-02-20 at 19 24 07" src="https://user-images.githubusercontent.com/48427733/154857870-124d38f8-e2cb-44d0-a99c-d0f8d9024274.png">



<img width="1211" alt="Screenshot 2022-02-20 at 19 24 26" src="https://user-images.githubusercontent.com/48427733/154857884-d59e1c70-4f25-4b3e-be7a-d67c1a0e54e7.png">



The first project, sales analysis is a PowerBI dashboard created from a sales data. The data had various fields such as categories, sub-categories, product, location, sales and profit.

I created a dynamic automated dashboard on PowerBI Pro Service, where you can interact with the data. This means that if you click on any of the graph data, the other data on the dashboard changes to represent that data. (Note: The document I uploaded is a PDF File, hence you cannot interact with it here, for that you need my PowerBI workspace access).
Secondly, I have divided the report into various categories, the first one listing sales and profit by month. The next one is by categories and sub categories, giving you the option to drill down into the data and analyse it at a granular level. The 3rd one is a map data, giving out profit and sales by U.S. States and the 4th one lists down quantity as a product of categories and sub categories.

This dashboard helps the user identify the top performing states, the highest grossing products and categories and the season where the business booms.


## IPL Matches Analysis - Excel and PowerBI

Check out the folder for the detailed report.
<img width="1050" alt="Screenshot 2022-02-20 at 19 30 02" src="https://user-images.githubusercontent.com/48427733/154858125-1ce3e15e-712a-4c10-81d6-65ad3b3e7b16.png">



<img width="972" alt="Screenshot 2022-02-20 at 19 30 18" src="https://user-images.githubusercontent.com/48427733/154858139-693c755e-f2db-486b-865b-3f25304fcf72.png">


<img width="1039" alt="Screenshot 2022-02-20 at 19 30 54" src="https://user-images.githubusercontent.com/48427733/154858159-cd984031-f649-4f22-9111-5257a2a4abdc.png">



Cricket is considered a religion in India, probably the largest. So it only seemed fitting to create a project on this. IPL, the Indian Premiere League is the world's largest league cricket tournament, held in India year after year. My analysis on this project ranged from analysing Batsmens', Bowlers' statistic over 10 years, the teams progress and the number of matches won/lost and the tosses as well.

This was a challenging project, with over 5 dataset related to each other, analysing the data and creating reports on them was a task which took me quite a while. The result is an amazing interactive dashboard uploaded on my PowerBI Pro workspace where you can analyse dozens of statistics with a single click. Click on a batsman score in a pie chart to see how he performed with respect to SR, Runs, 4s and 6s and more.

The project is still not complete since a dataset of this size needs justice by having more and more statistics and answering questions. I will try to update the project whenever possible.


## Nike Performance Analysis - Excel, Tableau and PowerBI

I recently worked on this short project, highlighting Nike's global performance across various markets and product segments. Finding the data was a hard task, since I could not find everything at a single source. Hence, I had to find data from various points, make it consistent and then run up visualisations.

Key Insights from this project: Nike sportswear is the best performing product, which recorded growth even during the pandemic, when other categories suffered losses. This can be linked to the fact that many non athletes starting doing regular exercises to stay fit in the pandemic.

<img width="1234" alt="Screenshot 2022-04-09 at 22 18 24" src="https://user-images.githubusercontent.com/48427733/162590302-6f7e7d1b-f853-4f19-9966-de761a450fc4.png">



North America is a stagnant market, showing signs of decline. Europe and China are key market, showing strong upward trend. North America still has the largest percentage of sales but europe is quickly catching to that number.

<img width="1219" alt="Screenshot 2022-04-09 at 22 18 39" src="https://user-images.githubusercontent.com/48427733/162590311-b912f228-844d-43d3-b711-dee530f59019.png">



Wholesale is the best performing channel. Nike has consistently outperformed key competitors, Puma and Adidas, keeping the market leader position to itself
<img width="1262" alt="Screenshot 2022-04-09 at 22 18 50" src="https://user-images.githubusercontent.com/48427733/162590317-af61d52f-ec3d-4b63-a223-934ed88beee8.png">

## Customer Analytics Using Python

Recently, I came across an interesting project, where Python is used for customer analytics on a variety of use cases ranging from acquisition, attrition, grouping, etc.

In this project, I have tackled 3 major use cases.

1. K Means Clustering (Unsupervised) to group problem types

In this use case, we have used K Means algorithm to group customer problems. The data provided was a list of problems and the time/resources spent to resolve them. We classify these problems into clusters using the key data such as count, time for response, reoccurence, etc.

Since K means requires you to provide the number of clusters in the beginning, and without having an idea of it, it might be challenging to identify the optinmal size. To resolve this, I used the Elbow Method to identify the optimal number of clusters.


<img width="1192" alt="Screenshot 2022-12-25 at 13 59 01" src="https://user-images.githubusercontent.com/48427733/209469194-9a386f0b-8ca1-475f-ab4d-3e8a9368ba53.png">

After this, I fit and predict my model and analyse them using certain Blox Plots.
<img width="1100" alt="Screenshot 2022-12-25 at 13 59 12" src="https://user-images.githubusercontent.com/48427733/209469213-e78290f3-3712-44ad-af9c-5472fac288d4.png">

Once the model is ready and accurate, I check how the problems in my training data has been classified into groups.

Finally, I use the model to predict the groups for new incoming customer problems.
<img width="1081" alt="Screenshot 2022-12-25 at 13 59 17" src="https://user-images.githubusercontent.com/48427733/209469251-bc9b08a8-a622-496d-9dfa-9704af2458a5.png">


2. Linear Regression Analysis to Identify Customer Lifetime Values for new Customers

In this use case, we predict the Customer Lifetime Value CLV for new customers based on their initial purchase history.

We create the model using our predictions and target training and testing data. We use r2 score to identify the accuracy.
<img width="1224" alt="Screenshot 2022-12-25 at 14 20 59" src="https://user-images.githubusercontent.com/48427733/209469692-4b7fbcb6-2560-44d3-a1a9-8f5be12b0e15.png">


We finally input fresh data to identify the CLV based on the model.
<img width="956" alt="Screenshot 2022-12-25 at 14 21 08" src="https://user-images.githubusercontent.com/48427733/209469696-66837499-7e96-43f3-b09f-4dabbe49c27f.png">





