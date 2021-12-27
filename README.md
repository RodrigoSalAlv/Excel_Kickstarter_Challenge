# Kickstarting with Excel

## Overview of Project
### Purpose
The purpose of this project is to see and find any tendency or characteristic in the outcomes based in a period of time in the category of 'Teather'; and any tendecy based in the goal, for plays only.

## Analysis and Challenges
In both analysis you need to now exactly what are you looking for or what are they asking you to look, it's important to get a picture in your mind and know the tools you have available to find the easiest path to get in to the results.

### Analysis of Outcomes Based on Launch Date
The first analysis can be made by using a pivot table, the new excel versions split the dates by month and is no necessary to get a new column extracting this information so that was very helpful. However a column with the year was necessary to get a filter and see the behavior of each year.

![image](https://user-images.githubusercontent.com/96214489/147415127-19733c5e-af8e-4503-93ca-aa0c6ff4c1f3.png)


### Analysis of Outcomes Based on Goals
In this case is easier and faster to use a "=COUNTIF()" formula rather than a pivot table, this is because you are working with ranges and conditions and it's a little more laborious with pivot tables. In case you prefer to work with pivot tables, you need to add a column categorizing each goal based in their value, to do this you need to use a very big "=IF()" formula.

Once you get the formula for the successful ranges you only need copy and paste to into the rest columns (not forgetting to fixing the columns inside the formula with the "$" symbol) and replacing the "Successful" word for "Failed" and "Canceled" and looking into de Formulas.

![image](https://user-images.githubusercontent.com/96214489/147415206-c99d732a-a278-4777-8c7b-8956208da721.png)


### Challenges and Difficulties Encountered
In the first analysis was a little challenging sort by outcome and put first the "successful" outcomes. However by placing the cursor in the right place and choosing the "Z to A" option was everything you need to do to get the result, also could be challenging work with pivots charts because not all the times excel understand what are you looking for and you need to change the formating or the data itself.

The second analysis was challening by the use of the formula "=COUNTIF()" this one could be a little hard becase it's little confusing to understand what the formula is counting, the same happens with the "=SUMIF()" formula. In this case, to prove you're doing the right thing you only need to go to your dataset and filter all the conditions to see everything is right.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
For the category of Theater along the months in multiples years we can see that the month with more successfull is May, one of the reason behind this result could be that for all the countries we have in our dataset, the most "shows" are in the countries of US, GB and CA where in May almost start the "summer" considered as the season when you can do more things outdoors. Another peaks we can see is in February and October, the successful of the shows could be thanks to "Valentines Day's" and the "Halloween Season" respectively.

In the "Failed" shows we can see the almost the same tendency as the "Successful" ones, there is more probabilty to get more "failed" shows when launch more than when you're not. However we can see that by the months of May, June, July and August we get a flat tendency almost getting the same quantity of shows canceled each month, the country with the most "Failed" shows in this months was US.

For the "Canceled" ones we can see a very few of them along the year, January is the month with most shows canceled. Many of them with a very high goal.

- What can you conclude about the Outcomes based on Goals?
The graph shows that the outcome of all shows directly depends in the goal for each one, we can see a tendency of reduction in "successful" and an increase in "failed"  when the goal is higher. This could tell us that perhaps the goal for some plays could be very high and unreachable
Also we can see a slight rebound in "successful" plays between $35000 and $45000 but they are just a few ones (6) from a total of 9 plays with this goals.

- What are some limitations of this dataset?
The limitations of this dataset is that it is only a sample, there's so much more information to see, we can only do a few analysis with the data we have. This info could increase so much more.
- What are some other possible tables and/or graphs that we could create?
We also can create a table and graphs of:
  The countries with the higher and lower quantity of successful, failed and canceled shows
  The quantity of shows with the higher incomes.
  The shows with more time since their launching until their ending.

