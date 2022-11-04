# Pizza Analytics: A data analytics project.

## What's the objective?
The objective of this mini project is to predict how many ingredients and of what kind would be needed in the
near future.

## What data structure do we want?
Probably some sort of dataframe is the best way to go. They are easy to manipulate and to work with. Panels
(3 dimensional) could have been a good idea, but they were deprecated long ago, and maybe it exceeds the level
of complexity required for such problem.

## Where can we start?
First and foremost, there are too many data files to work with that working with them can get quite messy, plus
some contain non-interesting data (such as order_details_id, which serves just like an index). It would be a
great idea to sum up those files in one compact dataframe. Just by a glimpse of it, the order details occupy
far too many rows for just one order. Perhaps, making lists or dictionaries with all the details of an order,
and write them on one single line, is more readable, and easier to work with.

Note that there is a data_dictionary file which specifies what does each column represent. Maybe we could add
those descriptions as metadata of a customized dataframe object.
