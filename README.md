# data-visualisation-challenge

## ****Project aim****

The aim for this project is to analyse data collected in mouse study with the use of different treatments along with the time period in days, to observe the size of tumor over the time for cancer treatment in pharmaceutical company. 


## **Project description**

This project uses Pandas Dataframe and Maplotlib to visualise our data into graph for easy analysis. In combination of using scipy stats to be used for our data distribution calculations to study the data reliability.

Jupyter notebook - under Visual Studio Code is heavily used to write the code for project analysis. 
Application of two different plot functions such as Pandas Dataframe Plot method, and Matplotlib pyplot are used to find out their differences in method and output. 


### **Benefits:**
 - Jupyter notebook has most of the packages available, simply just need to import them into the file before writing the code.
 - Using Pandas Dataframe to plot is easier, less codes used to generate the data.
 - The only benefit of Matplotlib is more parameters can be used to edit the plot.
 
### **Disadvantages:**
 - Using Visual Studio Code to work on this project for starter is more confusing, as need to prior know what packages to work on, and install beforehand. 
 - Using Matplotlib to process data visualisation is more complex, as data needs to be processesed and input separately. This includes x-axes tick numbering, tick labelling, tick locations, tick names and sort values in order.
 - Limited parameters to edit the plot using Pandas Dataframe plot method. 

## **Project method**

 1. First: open, and merge raw data given in Excel CSV to Pandas DataFrame
 2. Second: to find for abnormality, in this case, get rid of duplicates data. 
 3. Third: Start to process data, generates usual statistical calculations. 
 4. Fourth: Generate series of data required using Bar charts and pie charts with two method: Pandas Dataframe Plot method, and Matplotlib pyplot.
 5. Fifth: Generate Boxplots
     - Funtions used: Groupby method, reset_index(), last(): to determine last element appeared in the data (but not last row)
     - For loop method and if function used: to filter final tumor volume data to compare 4 treatments used
     - Series of Quartiles calculations used to determine outliers
 6. Sixth: Generate Line Graph
      - Randomly pick a mouse treated by Capomulin and analyse the progress of the treatment over the time. 
 7. Seventh: Generate Scatter plot and linear regression line to find out the correlation between weight of mouse and its tumor size. 
   
 ## **References**

   - Pandas Get List of All Duplicate Rows.(9 November 2021).Sparkby{Examples}. Retrieved on: 26 March 2023, from<https://sparkbyexamples.com/pandas/pandas-get-list-of-all-duplicate-rows/#:~:text=Pandas%20DataFrame.,multiple%20columns%20or%20all%20columns.>
   - How can I use the aggregate function in Python Pandas to calculate summary statistics?.(20 March 2023), GITNUS, Retrieved on: 27 March 2023, from<https://blog.gitnux.com/code/pandas-aggregate/>
   - Pandas.Series.sort_values.(2023).Pandas, Retrieved on: 27 March 2023, from <https://pandas.pydata.org/docs/reference/api/pandas.Series.sort_values.html>
   - How to select columns from groupby object in pandas?.(2014). Stack Overflow. Retrieved on: 27 March 2023, from<https://stackoverflow.com/questions/19202093/how-to-select-columns-from-groupby-object-in-pandas>
   - Iterate pandas dataframe. (2021). Python tutorial. Retrieved on: 28 March 2023,from:<https://pythonbasics.org/pandas-iterate-dataframe/>
   - Plot multiple boxplots in one graph in Pandas or Matplotlib.(01 February 2022). Tutorials Points, Retrieved on: 29 March 2023,from<https://www.tutorialspoint.com/plot-multiple-boxplots-in-one-graph-in-pandas-or-matplotlib>
   - Chart visualization. (2023). Pandas, Retrieved on: 29 March 2023,from<https://pandas.pydata.org/docs/user_guide/visualization.html>
   - pandas.DataFrame.sort_values.(2023).Pandas.Retrieved on: 29 March 2023, from:< https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.sort_values.html>
   - Box Plot (Box and Whiskers): How to Read One & How to Make One in Excel, TI-83, SPSS.(2023).Statistics How To Statistics for the rest of us!, Retrieved on: 30 March 2023,from:<https://www.statisticshowto.com/probability-and-statistics/descriptive-statistics/box-plot/>
   - How to Identify Skewness in Box Plots.(5 May 2021). Statology.Retrieved on: 30 March 2023,from:< https://www.statology.org/box-plot-skewness/>
   - README 101. (n.d.). Make a ReadMe. Retrieved on: 30 March 2023,from:<https://www.makeareadme.com/>

