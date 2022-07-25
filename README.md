## International Football X D'Challenger June Challenge

I have been a part of the International Football X D'Challenger June Challenge

## [About the Challenge](https://www.linkedin.com/feed/update/urn:li:activity:6943269318788820992/)


## Overview:
I was provided one excel file which contained 3 datasets: Data Dictionary, Results and Shootouts
Results data mainly contains information about the home-team, away-team and venue on which it was played and goals scored by the team, but point to note here is that there was no columns mentioned about the "Winner" of the match.
Another dataset mentioned is the "Shootouts" which mentions about the penalty shootout teams and the winner.
And, "Data Dictionary" mentions about the dataset and goal of the project.

## Objective:
* Who is the best team of all time?
* Which teams dominated different eras of football?
* What trends have there been in international football throughout the ages? home advantage, total goals scored, distribution of teams' strength etc?
* Which teams are the most active in playing friendlies and friendly tournaments? does it help or hurt them?

## Tools Used: Power BI, Flaticon website ( for icons )


After loading the dataset in Power BI, I applied following operations:

## Steps Taken in Power BI Desktop Application:

* First of all, I started with the "Result" Dataset where my first task here was to find the winner among the teams played. So, I made a column in Power BI named "Winner", where I used the DAX logical operator to find the Winner team or tied matches too as shown below.

## Original Excel Page:

![original excel ss](https://user-images.githubusercontent.com/72240938/180409250-06bbeb4a-ef01-4005-8d73-0021fdd26fc3.jpg)

## After application of DAX operator in Power BI to get the Winner column:
![pg 1](https://user-images.githubusercontent.com/72240938/180410086-c3cffc3f-0ee4-4397-9677-188654dbd5a6.jpg)

* Second task was to find the "Year" from the dataset, where I used again a simple DAX operator for finding year from the Date column as shown:

![Year column new](https://user-images.githubusercontent.com/72240938/180410870-472e2487-81d4-42dd-b8dc-722698fd810d.jpg)

* Now, I made 2 tables separately by using "FILTER" DAX operator in Power BI to get the Tied matches and Friendly Tournament tables in Power BI for further analysis.

## Tied Matches Table:

![tied table](https://user-images.githubusercontent.com/72240938/180413797-a741238f-2715-49d8-9591-93bd036dc02f.jpg)

## Friendly Tournament Table:

![Friendly table](https://user-images.githubusercontent.com/72240938/180413923-621abf23-4771-4378-882b-be88d36da6f4.jpg)

* I applied some DAX measures in the table to find the types of tournaments,  no. of countries hosted, number of tied matches, number of games played and number of friendly tournaments.


## Design and Visualization Part:

Now, I took a plane background for this dataset. And, the color palette which I used was green, white and blue for it. I used the flaticon website to import icons from there to use in the report.

After then, I applied the bar charts, area charts and cards in the report to make the entire report according to the objective required. 

## Key Insights from the report:

* Brazil has most number of wins.
* Friendly matches has helped the teams and they secured more wins in those matches. Those countries are Germamy, Hungary and Sweden ( analysis was done on the total number of matches played by the teams in friendly matches as home and away teams, and then finding winner from those teams.
* Away teams has scored more overall goals in a year according to the data in the entire matches played.


## Conclusion:
Overall, it was a nice dataset to work around with and I loved to visualize the dataset and come with the insights from it.


## [Dashboard Link] (https://app.powerbi.com/links/mh9M3sbkme?ctid=41ef9d53-cb31-4b40-a55d-0893334a4059&pbi_source=linkShare&bookmarkGuid=c2ef01dc-22f8-4966-9dc0-4166433fe068)

