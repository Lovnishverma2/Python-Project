Python Visualization Project using Matplotlib & Seaborn

In this project, we'll explore various visualization techniques using Matplotlib and Seaborn libraries in Python. We'll create visualizations
for different types of data, including line plots, scatter plots, pie charts, histograms, multiple plots, subplots, 3D plots, and Seaborn's
scatter plots, count plots, pair plots, distplots, and heatmaps.

Libraries Used:

Jupyterthemes (for theme)
NumPy
Matplotlib
Pandas
Seaborn (Statistical data visualization)

1. Plot basic line plot
   Data file used: stock_data.csv

2. Plot Scatter plot
   Data file used: Stock_daily_return.csv

3. Plot Pie chart
   Creating own values

4. Plot Histograms
   Data file used: stock_daily_return.csv

5. Plot Multiple Plots
   Data file used: stock_data.csv

6. Plot Subplots
   Data file used: Stock_data.csv

7. Plot 3D Plots

  from mpl_toolkits.mplot 3D import Axes 3D

8. Seaborn Scatterplot & Count plot
  Library used: Seaborn

  import seaborn as sns
  from sklearn.datasets import load_breast_cancer 
  cancer = load_breast_cancer()

. Scatter plot
. Count plot

9. Seaborn Pairplot, Displot & Heatmaps/correlations

. Pair plot
. Heat map
. Distplot

  sns.pairplot(data)
  sns.heatmap(data.corr(), annot=True)
  sns.distplot(data['Column name'])
  
--Separate distplots:

  sns.distplot(data1['column_name'])
  sns.distplot(data2['column_name'])

This comprehensive Python visualization project showcases the power of Matplotlib and Seaborn libraries in creating insightful visualizations for
different types of data, making it easier to understand and interpret complex datasets.
