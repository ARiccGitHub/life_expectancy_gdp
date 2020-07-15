
My Python Data Visualization with the Library Matplotlib Seaborn Practice Project From:

Codecademy Data Science course Python, Data Visualization with Seaborn Matplotlib and Jupyter Notebook

Capstone
Visualize data from the World Health Organization with Seaborn
Seaborn Project Cumulative

----------------------------------------------------------------------------------------

Project Requirements:

Python v2 or later:
https://www.python.org/


Matplotlib
https://matplotlib.org/

Seaborn:
https://seaborn.pydata.org/

Jupyter notebook:
https://jupyter.org/

----------------------------------------------------------------------------------------

Overview:

In this project, we will be visualizing and looking for insights in a dataset from Kaggle (https://www.kaggle.com/fkosmowski/kivadhsv1), 
that contains information about loans awarded by the non-profit Kiva (https://www.kiva.org/).

Using Seaborn, we will explore the average loan amount by country using aggregated bar charts, 
and visualize the distribution of loan amount by project type and gender using box plots and violin plots.

You will be completing this project on your computer, similar to the other off-platform projects that we’ve done during this path.

WORKING ON YOUR COMPUTER
Learn about Jupyter Notebooks, a cool way of combining Python code with explanations or instruction in a web terminal.

----------------------------------------------------------------------------------------

Links:

My Blog, Life Expectancy and GDP
https://www.alex-ricciardi.com/post/life-expectancy-and-gdp

----------------------------------------------------------------------------------------

Project map:

Python Jupiter code lines file:
life_expectancy_gdp.ipynb

data files:
data/*.csv

chart images:
chrat/*.png

----------------------------------------------------------------------------------------

Project:

Step 1. Import Python Modules
	Import the modules that you'll be using in this project:

		
Step 2. Prep The Data
	To look for connections between GDP and life expectancy you will 	need to load the datasets into DataFrames so that they can be 	visualized.

Step 3. Examine The Data
	The datasets are large and it may be easier to view the entire 	dataset locally on your computer. You can open the CSV files 	directly from the folder you downloaded for this project.

Step 4. Tweak The DataFrame

Step 5. Bar Charts To Compare Average
	To take a first high level look at both datasets, create a bar 	chart for each DataFrame:

Step 6. Violin Plots To Compare Life Expectancy Distributions
	Another way to compare two datasets is to visualize the 	distributions of each and to look for patterns in the shapes.

Step 7. Bar Plots Of GDP and Life Expectancy over time
	We want to compare the GDPs of the countries over time, in order to 	get a sense of the relationship between GDP and life expectancy.

	First, can plot the progession of GDP's over the years by country 	in a barplot using Seaborn. We have set up a figure with the 	correct dimensions for your plot. 

Step 8. Scatter Plots of GDP and Life Expectancy Data¶
	To create a visualization that will make it easier to see the 	possible correlation between GDP and life expectancy, you can plot 	each set of data on its own subplot, on a shared figure.
	
Step 9. Line Plots for Life Expectancy
	In the scatter plot grid above, it was hard to isolate the change 	for GDP and Life expectancy over time. It would be better 	illustrated with a line graph for each GDP and Life Expectancy by 	country.


Step 10. Line Plots for GDP
	Let's recreate the same FacetGrid for GDP now. Instead of Life 	Expectancy on the Y axis, we now we want GDP.

Step 11. Researching Data Context
	Based on the visualization, choose one part the data to research a 	little further so you can add some real world context to the 	visualization. 

Step 12. Create Blog Post
	Use the content you have created in this Jupyter notebook to create 	a blog post reflecting on this data.
