# Declarative-Visualization-in-Python
Use Altair for Visualization and Jupyter notebook in Python<br />
Step 1: Import and Installing Required libraries and packages 

Step 2: Setting Directory and Reading File<br />
Subsetting the Data Set<br />

Step 3: Creating a Bar Chart Visualization in Altair <br />
A bar chart Visualization showing Top 10 states of COVID-19 cases<br />
Group the data by ST_Name(which is States in the US), use the rank function of altair and sort the data by the count of sum of confirmed cases in the United States to display the bar chart<br />

Step 4: Creating an Interactive Visualization in Altair <br />
An interactive visualization of confirmed cases and deaths across top 5 states(calculated above) in the US<br />
One of the unique features of Altair, inherited from Vega-Lite, is a declarative grammar of not just visualization, but interaction<br />
Since we see over plotting of points towards the bottom left side of the chart, add an element of interactivity which will help us zoom in and out of the chart to see the data points more clearly and a little more spread out
