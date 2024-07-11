# IBM-data-visualization-with-python


## Final Project Overview

Analyzing the Impact of Recession on Automobile Sales
You have been hired by XYZAutomotives as a data scientist. Your first task is to analyze the historical data and give the company directors insights on how the sales were affected during times of recession. You will provide a number of charts/plots to visualize the data and make it easy for the directors to understand your analysis.

Instructions for submission
You will be required to upload images showing your plots or dashboards, for your peers to review and award points. For each task you will be directed to save your images locally with a specific name. We rcommend that you create a local folder and save all your images there for easy reference.

At the end of each task, you are provided with the name to save your plot/chart image.

For example:

Save this plot as "Line_Plot_1.png"
*Hint: You can right lick on the plot and then click on "Save image as" option to save it on your local machine*
About the dataset
In this assignment you will be presented with varies question for analysing data to understand the historical trends in automobile sales during recession periods.

recession period 1 - year 1980

recession period 2 - year 1981 to 1982

recession period 3 - year 1991

recession period 4 - year 2000 to 2001

recession period 5 - year end 2007 to mid 2009

recession period 6 - year 2020 -Feb to April (Covid-19 Impact)


The data used in this lab has been artifically created for the purpose of this assignment only. No real data has been used.

**Data Description**

The dataset includes the following variables:

Date: The date of the observation.
Recession: A binary variable indicating recession perion; 1 means it was recession, 0 means it was normal.
Automobile_Sales: The number of vehicles sold during the period.
GDP: The per capita GDP value in USD.
Unemployment_Rate: The monthly unemployment rate.
Consumer_Confidence: A synthetic index representing consumer confidence, which can impact consumer spending and automobile purchases.
Seasonality_Weight: The weight representing the seasonality effect on automobile sales during the period.
Price: The average vehicle price during the period.
Advertising_Expenditure: The advertising expenditure of the company.
Vehicle_Type: The type of vehicles sold; Supperminicar, Smallfamiliycar, Mediumfamilycar, Executivecar, Sports.
Competition: The measure of competition in the market, such as the number of competitors or market share of major manufacturers.
Month: Month of the observation extracted from Date.
Year: Year of the observation extracted from Date.
By examining various factors mentioned above from the dataset, you aim to gain insights into how recessions impact automobile sales for your company.

This Project will be completed in 3 Parts:

Part 1: Create Visualizations using Matplotlib, Seaborn & Folium
Part 2: Create Dashboard using Plotly and Dash
Part 3: Submit your project and evaluate your peers


## Part 1: Create visualizations using Matplotib, Seaborn & Folium

Objective:
The objective of this part of the Final Assignment is to analyze the historical trends in automobile sales during recession periods. The goal is to provide insights into how the sales of XYZAutomotives, a company specializing in automotive sales, were affected during times of recession.

In this lab you will create visualizations using Matplotlib, Seaborn, Pandas.

**Tasks to be performed**

TASK 1.1: Develop a Line chart using the functionality of pandas to show how automobile sales fluctuate from year to year.

TASK 1.2: Plot different lines for categories of vehicle type and analyse the trend to answer the question “Is there a noticeable difference in sales trends between different vehicle types during recession periods?”

TASK 1.3: Use the functionality of Seaborn Library to create a visualization to compare the sales trend per vehicle type for a recession period with a non-recession period.

TASK 1.4: Use sub plotting to compare the variations in GDP during recession and non-recession period by developing line plots for each period.

TASK 1.5: Develop a Bubble plot for displaying the impact of seasonality on Automobile Sales.

TASK 1.6: Use the functionality of Matplotlib to develop a scatter plot to identify the correlation between average vehicle price relate to the sales volume during recessions.

TASK 1.7: Create a pie chart to display the portion of advertising expenditure of XYZAutomotives during recession and non-recession periods.

TASK 1.8: Develop a pie chart to display the total Advertisement expenditure for each vehicle type during recession period.

TASK 1.9: Develop a lineplot to analyse the effect of the unemployment rate on vehicle type and sales during the Recession Period.

## Part 2: Create Dashboard using Plotly and Dash

Objective:
The objective of this part of the Fnal assignment is to create dashboards to contain your plots and charts and to provide the directors with the ability to select a particular report or a period of time so they can discuss the data in detail.

In this lab you will create dashboards using Dash and Plotly and then add user-interactions to your dashboards.

Creating dashboards and adding customizations to the dashboards
The directors of XYZAutomobiles have requested a dashboard to be developed so they can drill into the data in more detail for specific years or by different categories. Your second task is to create a suitable dashboard and add in user interactions so that the directors can select the data they want to review without the need to request new plots.

**Tasks to be performed**

TASK 2.1: Create a Dash application and give it a meaningful title.

TASK 2.2:Add drop-down menus to your dashboard with appropriate titles and options.

Task 2.3: Add a division for output display with appropriate id and classname property

TASK 2.4: Creating Callbacks; Define the callback function to update the input container based on the selected statistics and the output container.

TASK 2.5: Create and display graphs for Recession Report Statistics.

TASK 2.6: Create and display graphs for Yearly Report Statistics.

## Part 3: Submit your project and evaluate your peers

Once you have completed the labs and saved all your files locally you will submit your assignment which will be graded by your peers who are also completing this course during the same session.


Good Luck!!
