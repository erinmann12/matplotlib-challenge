# matplotlib-challenge

**Background**

This project was based on data from the company Pymaceuticals Inc., a pharmaceutical company based out of San Diego. The company specializes in anti-cancer pharmaceuticals and most recently began screening for potential treatments for squamous cell carcinoma -- a commonly occurring form of skin cancer.

For this project, I was tasked with analyzing a study of 249 mice identified with SCC tumor growth that were treated through a variety of drug regimens. Tumor development in the mice was observed and measured over the course of 45 days. Researchers were interested in the performance of the drug Capomulin against other drugs of interest.

I was tasked with generating all of the tables and figures needed for technical report. 

**Tools Used**

1. Python
2. Pandas
3. Matplotlib
4. Jupyter Notebook
5. Numpy
6. SciPy

**Project Tasks**

Before analyzing the data, I had to clean the data by removing any duplicate Mouse Id time points from the data set. 

![](C:\Users\erinc\Desktop\BootCamp\Homework\matplotlibhw\matplotlib-challenge\Images\clean_mice_data.PNG)

Next, I created a summary statistics table for each drug regimen that included the mean, median, variance, standard deviation, and SEM. 

Using Panda's DataFrame.plot() and Matplotlib's pyplot, I created a pie plot and a bar plot to show different measurements of data. Next, I calculated the quartiles and IQR of each treatment regimen and created box plots to show the figures. Finally, I created scatter plots for a mouse that was treated with Capomulin and calculated the correlation coefficient and linear regression model between the mouse's weight and average tumor volume for the treatment. 