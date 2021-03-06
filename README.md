# **Kickstarting with Excel**

## Overview of Project.

This is my firt project in the Data Analysis and visualization boot camp of the University of Texas at Austin.
It is a good opportunity to work with real data from Kickstarter.
**But what is Kickstarter?** Well, it is a funding platform for creative projects.
Every project creator sets their project's funding goal and deadline. 
If people like the project, they can pledge money to make it happen. 
If the project succeeds in reaching its funding goal, all backers' credit cards are charged when time expires.

_You can access the website of [Kickstarter here](https://www.kickstarter.com/)._

For this exercise we will analyze a data set  in a spreadsheet called [Kickstarter challenge](ckstarter_Challenge.xlsx) and will look at how plays did in terms of percentage of success and failure in different goal group.
We will also analyze the outcomes of the theater outcomes by launch date.


### Purpose

- The objective of this challenge is to utilize the excel skills  that we learned in Module 1.
- We'll also start analyzing the visualizations (Pivot Graphs) in order to be able to tell a story based on the data.



## Analysis and Challenges

- I had the opportunity to make some tables and graphs and I could get some interesting insights from them.
- Generally speaking I had to pay special attention to every line in the instructions, If you don't do this you can miss an important instruction and have an incomplete task in the challenge.


### Analysis of Outcomes Based on Launch Date

- The specific challenge in this activity was creating the pivot table and the graph at the same time. I used to create first the pivot table and then  create the graph but i had the opportunity to make both at the same time.
- I could use a function called "YEAR" that practically gives you only the year of a given date.
- I could use the filters in the pivot table and see how the graph responds to these filters too.
- <img src = "resources/Outcomes_vs_Goals.png" width= "500" >

	- You can see the image of [Outcomes Based on launch date](resources/Outcomes_vs_Goals.png) here.


### Analysis of Outcomes Based on Goals

- The challenge in this activity was to use the function **COUNTIFs**, personally I had not used this function before and being able to determine several conditions in different columns was great.
- **"SUM" & "AVERAGE**  were other two interesting functions in this activity and I was amazed how  thay simplify the calculations
- <img src = "resources/Theater_Outcomes_vs_Launch1.png" width= "500" >

	- You can see the image of [Theater Outcomes by Launch Date1](resources/Theater_Outcomes_vs_Launch.png) here.


### Challenges and Difficulties Encountered

-I found these tasks very interesting, Even when I have used excel a lot I could definitely find new things to learn.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

	1. We can clearly see that the events that are launched in the months of May , Jun and Jul have a better success/fail ratio . The weather could be a factor here.
	2. We can also see there are fewer events launched in the months of Nov, Dec and Jan and that the success/fail ratio drops drastically in December

- What can you conclude about the Outcomes based on Goals?
	1. We can clearly see the higher the goal the higher the probability of failure.
	2. We can see that if the goal is less than $20,000 the chances of success are higher.

- What are some limitations of this dataset?

	There is no demographic data about the backers, If we had it, it could help us get insights about how data like age, gender, marital status income, education can influence in the results and success of the events
	

- What are some other possible tables and/or graphs that we could create?

	- I used the "maps" option , and the funtions vlookup and match to creare a graph that lets you choose from a drop-down menue the options:

		-- Sum of goal
		--Sum of pledged
		--Percentage Funded
		--canceled %
		--failed %
		--successful %

	- <img src = "extra_resources/map_successful1.png" width= "500" >

	- <img src = "extra_resources/map_failed.png" width= "500" >

	

	- I created another pivot graph where we could see how much other countries ( Except US) have in  the success , failed and canceled fields.
	- <img src = "extra_resources/success_failed_cancel_except_us.png" width= "500" >

	- Below we can see another graph where with count of backers in the primary  axis Y and the pledged amount in the secondary Axis Y
	- <img src = "extra_resources/Backers_count_vs_pledged.png" width= "500" >


