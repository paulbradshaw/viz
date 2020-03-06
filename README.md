# Resources for data visualisation exercises

You can [download data on donations (as well as loans, spending and other information) to political parties on the Electoral Commission website](http://search.electoralcommission.org.uk).

If you just click 'search' and scroll to the bottom where individual donations are shown in a table, there should be an option to **Export Results** as a CSV.

This data is good to use to explore data visualisation because it allows us to use a range of different charts for different purposes.

In this repo you can find a CSV of data downloaded in June 2019. There is also an XLSX file which shows that data being analysed in different ways to generate data for different charts. For example:

* Pivot [table] total donations by party - the top 5 are then used for a pie chart (composition)
* Pivot totals by non-party - the top 10 are used for a bar chart (comparison)
* Extract month/year - we need to do this to show distribution on a histogram, or change over time in a line chart, because the data only includes specific dates
* Pivot totals by month - to create a histogram showing distribution of donations over a typical year
* Pivot stacked bar: we use a field for columns but filter to just 2 of those that can be used to show both comparison (between bars) and composition (within the bar)
* Pivot year and party: to create a line chart showing change over time

## Cleaning data for mapping

Open Refine is useful for converting data from XML or JSON format, combining data, and cleaning it. 

[This tutorial explains how to convert, combine and clean food hygiene data so that it can be mapped](https://github.com/paulbradshaw/viz/blob/master/cleaningformapping.md)

## Mapping points (Datawrapper)

Here's [how to create point maps in Flourish](https://github.com/paulbradshaw/mapping/blob/master/flourishpoints.md).

[This tutorial explains how to create a map of points in Datawrapper](https://github.com/paulbradshaw/mapping/blob/master/datawrapperpoints.md). However, its zoom level doesn't go very far so it's only suitable for national-level stories.

Here's [how to make choropleth maps in Flourish](https://github.com/paulbradshaw/mapping/blob/master/shapesflourish.md)

Flourish does have a [timelapse map of points](https://github.com/paulbradshaw/mapping/blob/master/flourishpointstime.md), too.

You can create a cartogram election map in Datawrapper - [details here](https://github.com/paulbradshaw/mapping/blob/master/datawrapperelection.md)
