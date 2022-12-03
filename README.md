# data_analysis

**Vending Machine sales dataset**

Source: https://www.kaggle.com/datasets/awesomeasingh/vending-machine-sales

The analysis of this dataset has as goal to demonstrate descriptive analysis and dashboard creation in Excel and Power BI.
The dataset regarding sales of vending machines in 4 locations in Central New Jersey.

The questions that will be answered are the following:

1. Which is the best selling location?
2. Which are the top 5 best selling/grossing products?
3. How could each location improve its sales?

Methodology: 1. Overview of the dataset in Excel, creation of pivot tables with the most important information and using their graphs to create a comprehensive dashboard. Subsequently a similar comprehensive dashboard is created in Power BI in oder to answer the above questions.

**Preparation**: 
1. There are blank cells in the Category column in the original dataset and 3 lines with both Category and Product blank. Those 3 lines are not taken into account, the missing category items were filled manually by Google searching the respective products. 
2. For our analysis it is useful to isolate the month each transaction took place. This was achieved by splitting the "TransDate" column using the "Text to Columns" feature in Excel.
3. For the purpose of the analysis I created an analysis table using only the columns necessary for analyzing our dataset.

**Answers**: 
1. **Which is the best selling location?** 

At first glance the location "Gutten Plans" is the best selling location.
<img src="https://user-images.githubusercontent.com/69303154/205448993-718cbeca-1a87-474d-b43d-95746cf42a8c.png" width="1000" height="400">
However after carefully examining our dataset we can see that the location "EB Public Library" started operations in March. If we exclude the first two months as a result the outcome is the following:

<img src="https://user-images.githubusercontent.com/69303154/205449126-05cda174-c593-469a-ac78-1cbbe2c1efb6.png" width="500" height="200"> <img src="https://user-images.githubusercontent.com/69303154/205449177-965a0453-48ad-4e7e-9616-e835268b0a32.png" width="500" height="200">
Additionally we see that March sales are low which leads us to check our dataset the first day of operations. The first day this location operated is the 14 March which means the first complete month of operation is April. So from April onwards the location (From this month onwards all locations in comparison are fully operating) "EB Public Library" is the best selling location.

<img src="https://user-images.githubusercontent.com/69303154/205450878-a52bce48-d1fa-4e4c-b4e0-0d990795c274.png" width="1000" height="400">





