# DataVisualistaion_Challenge
# Dowload provided files
TASKS
# Prepare the data.
Display the number of unique mice IDs in the data, and then check for any mouse ID with duplicate time points. Display the data associated with that mouse ID, and then create a new DataFrame where this data is removed. Use this cleaned DataFrame for the remaining steps.

# Generate summary statistics.

# Create bar charts and pie charts.
Generate two bar charts. 
Create the first bar chart with the Pandas DataFrame.plot() method.
Create the second bar chart with Matplotlib's pyplot methods.
Generate two pie charts. Both charts should be identical and show the distribution of female versus male mice in the study.
Create the first pie chart with the Pandas DataFrame.plot() method.
Create the second pie chart with Matplotlib's pyplot methods.

# Calculate quartiles, find outliers, and create a box plot.
Create a grouped DataFrame that shows the last (greatest) time point for each mouse. 
Create a list that holds the treatment names as well as a second, empty list to hold the tumor volume data.
Loop through each drug in the treatment list, locating the rows in the merged DataFrame that correspond to each treatment. Append the resulting final tumor volumes for each drug to the empty list.
Determine outliers by using the upper and lower bounds, and then print the results.

# Create a line plot and a scatter plot.
Using Matplotlib, generate a box plot that shows the distribution of the final tumor volume for all the mice in each treatment group. 
Select a single mouse that was treated with Capomulin, and generate a line plot of tumor volume versus time point for that mouse.
Generate a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.

# Calculate correlation and regression.
Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.
Plot the linear regression model on top of the previous scatter plot.







