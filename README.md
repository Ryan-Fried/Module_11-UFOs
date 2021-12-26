# Module_11-UFOs

# Overview

The purpose of this project was to build off a webpage constucted in the module which filters a table and displays the results in a webpage. In this project, we expanded the capabilities of the webpage by adding additional filters which can be used in any combination to sort the table.

# Results

The functionality of this webpage is fairly self explanatory. The webpage features a table displaying UFO sightings in the United States and Canada from the first two weeks of January 2010. Five filters can be applied to sort the table in any particular combination: date, city, state, country, and shape. The data set is not particularly large, so the sort feature seems to be the most affective when using fewer of the filters. For instance, multiple filtering criteria may not result in any outcomes unless the user is looking to specifically locate data they know can be found in the table. Initially, the page displays the unfiltered table and five filtering boxes containing sample text:

![Screenshot (163)](https://user-images.githubusercontent.com/91569387/147391782-7a020cd6-e3e0-43ac-a2e1-882dcee0431f.png)

The best way to navigate the webpage would be to begin with one or two filters to narrow the data slightly, as opposed to using all five filters at once, unless looking for very specific data, given the scale of the dataset. For instance, filtering by date narrows to all the events from a certain day:

![Screenshot (164)](https://user-images.githubusercontent.com/91569387/147391783-64cf4ed7-19b2-4367-b476-aaf074b1403e.png)

From there we can add another filter to sort the results even further. Adding a search criteria of events located in the state of California here reduces the table to two rows:

![Screenshot (165)](https://user-images.githubusercontent.com/91569387/147391784-0d4b2af1-f9c7-4d07-b497-d6c9204372bd.png)

We can search even further if we want the table to display a single result:

![Screenshot (166)](https://user-images.githubusercontent.com/91569387/147391785-3ecf98dd-fcab-4e14-a24a-b65b1da6a36c.png)

# Summary

One simple drawback of this design is that while the tool is usefull, it would better serve much larger datasets, where filtering by multiple criteria would be more applicable. Despite this, filtering options could be added so that the table is sortable by any row or data point. One major improvement that could be made to improve the functionality of the webpage would be to filter by range rather than by a single data point. Instead of searching for dates by specific day, we could then sort within a range of days. On a similar note, we could allow for multiple inputs in each filtering box, delimiting by a comma for example. Thus, we could search for shape: 'light, circle", or state: 'ca, ny, tx', or other such criteria.
