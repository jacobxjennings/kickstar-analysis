# Kickstarting with Excel

## Overview of Project
The purpose of this project is to use Microsoft Excel to analyze a large dataset. 

### Purpose
The purpose of this analysis is because Louise wants to understand their past fundraiser campaign to improve upon their future campaigns. By analyzing historical data, we are able to make many different conclusions. For example, you can understand when the best time of a year to launch a fundraiser has been successful in the past. You can determine realistic goals for future fundraisers, and you can forecast future campaigns more accurately.

## Analysis and Challenges
To start the analysis, you must first understand the data. This dataset has around 4000 data point, or fundraising campaigns, across many different countries, years, categories, etc. To better understand the data, visually, some columns can be color coded with Conditional Formatting For example, the image below shows the outcomes column being formatted with "Successful" being green and "Failed" being red. 

![Conditional Formatting Example](https://github.com/jacobxjennings/kickstar-analysis/blob/main/Resources/conditional_formatting_example.PNG?raw=true)

After these step, you can start to analyze and make assumptions based on the data.

### Analysis of Outcomes Based on Launch Date
Once you understand the basics of the data, you can start to draw concusions from the data. The pivot table, "Theater Outcomes by Launch Date," shows that historically there are more successful campaigns started in the middle of the year for the theater category. More specifically, May is historically the best month to launch a fundaraiser, while December is the worst. 

![Outcomes vs Launch Date](https://github.com/jacobxjennings/kickstar-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals
This chart indicates that fundraisers with the lowest inital goal tends to be more successful. The chart below shows that the success rate of a fundaraiser decreases until around 30,000 to 34,999, where the success rate jumps back up to around the same level as the 5000 to 9999 category. 

![Outcomes vs Goals](https://github.com/jacobxjennings/kickstar-analysis/blob/main/Resources/Outcomes_vs_Goals.png?raw=true)

### Challenges and Difficulties Encountered
I did not really come around any challenges with the dataset. Since it is so large, there is a small learning curve with being first introduced. However, once you are familiar with the dataset, drawing conclusions from it was pretty easy. 

## Results

We can make the following conclusions from this dataset:

- First and foremost, May is the best month to launch a fundraiser across all categories (not just Theater).

- Fundaraisers should be launched with the inital goal of less than $9999 since anything past that has more than a 50% chance of failure.

The main limitation this dataset has is that the dataset doesn't include any target audience, market size, or marketing budget/costs to indicate how much time and resources are going into advertising for this campaign. There is also no estimate of the amount of people they are marketing to, to get a better understanding of the success rate of a specific fundaraiser.
