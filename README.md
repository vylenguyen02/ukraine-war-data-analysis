This is my CS181 - Data Systems final project in which we used data analysis methods to answer our central question: 

    **What are the major factors contributing to the huge number of casualties in the Russia - Ukraine war**

For this project, we used Python, SQL, Python pandas library, requests for web-scraping data, and plotly library for data visualizatons (graphs, tables,etc)

Two datasets that we picked are: 

1. Russia - Ukraine war total casualties (JSON File) Source: https://www.kaggle.com/datasets/299939cceb4d5b67df96794141a0e2ee74fd0f054ab61f72afbfbde27a0ae8e7?resource=download&select=russo-ukraine-war-casualties.json

2. Wikipedia website: Casualties in the Russia - Ukraine war 

-> Web-scraping two tables Civilian Deaths and Dead Foreign Fighters in the Wikipedia web page while the JSON File was just parsed and processed directly


**Data Analysis:**
- From the DataFrame of the table Civilian Deaths' subset, we can see that areas that are adjacent to Russia (Chernihiv, Kharkiv, Luhansk, Mariupol - Eastern Ukraine) have the most number of civilian casualties, except for Kyiv because the Russians have to emphasize their military forces on the capital city of Ukraine in their operation.

- The bar chart of the table Dead foreign fighters indicates that the majority of foreign fighters are volunteers going to Ukraine to fight for the Ukrainian Armed forces while the Russian army, with the support of The Donetsk Armed forces and Luhansk Armed forces because they are pro-Russian paramilitaries in the Donbas region of eastern Ukraine

- The table Total losses indicates that the majority of vehicles/weapons is constantly inscreasing, indicating that there were more and more military vehicles/weapons are used in Ukraine except for the BM-21 Grad (mlrs_grad), Buk missile system, and ships which were not utilized much throughout the time period


**OUTCOME OF THE PROJECT - ANSWERING THE CENTRAL QUESTION:**

1. Areas: the closer they are to Russian border, the more casualties there are

2. A lot of foreign fighters volunteering to fight alongside Ukrainians with numerous fighting for Russian people's militas in Ukraine's Donbas region

3. The constant increase in weapons and military vehicles being supplied to the Russian army during the war
