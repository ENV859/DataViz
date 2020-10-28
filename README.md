Source: https://towardsdatascience.com/plotting-with-pandas-an-introduction-to-data-visualization-8bd7c0831650

We are going to explore the data visualization capabilities of Pandas.  We’ll start by introducing the basics — line graphs, bar charts and pie  charts — and then we’ll take a look at the more statistical views with  histograms and box plots. Lastly, we’ll see how we can create multiple  plot in one chart and how we save charts as images, so we can utilize  them in our own reports, documents and web pages.

Throughout the tutorial you will use a dataset about the weather in London, UK,  and you’ll create a number of charts using that data. I have created  this dataset from public domain information that is available from the  UK Meteorological Office.

# Plotting with Pandas

https://projectcodeed.blogspot.com/2020/02/plotting-with-pandas-introduction-to.html

Fundamentally, we are talking about a set of methods that can be used with a Pandas  DataFrame to plot various graphs from the data contained in that  DataFrame. It relies on a Python plotting library called **matplotlib**.

The purpose is to simplify the creation of graphs and plots, so you don’t  need to know the details of how matplotlib works. However, you will  need to know one or two matplotlib commands but they are very simple and I’ll explain them as we get to them.

You can think of matplotlib as being a ‘backend’ for Pandas that takes care of the mechanics of creating a plot.

1. Import libraries

2. Get data

3. Basic plots: Examples & syntax

   1. Line
   2. Multi-line
   3. Bar and Horizontal bar
   4. Scatter
   5. Pie

   NOTES:

   * Different formats for different purposes
   * Components of charts: axes & aesthetics (titles, labels, legends)
   * Use of indices

4. Statistical plots:

   1. Boxplot
   2. Histograms

5. Advanced plotting

   1. Multiple plots (subplots)
   2. Saving plots

6. [Customizing plots](https://towardsdatascience.com/5-easy-ways-of-customizing-pandas-plots-and-charts-7aefa73ff18b)

   1. Changing size and color
   2. Setting a title
   3. Display a grid
   4. Changing the legend
   5. Customizing the ticks
   6. Recycling formats using `**kwargs`