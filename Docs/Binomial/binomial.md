# Importing

To use the Binomial class, simply import by typing:
```from EasyStatistics import Binomial```

## Creatng an object of the class

An object can be created like:

```B1 = Binomial(0.6, 20)```

**0.6** is the probability, while **20** is the size of the data.

## Adding dataset

If we want to include our own dataset, we can do so by calling this function:

```Prob, Size = replace_stats_with_data()```

This returns two values:

* Probability of the data
* Size of the data

## Calculating mean

We can calculate the mean of our dataset using the function:

```Mean = calculate_mean```

This returns a single value, which will be the mean of the data.

## Calculating standard deviation

We can calculate standard deviaton using the following function:

```STD = calculate_stdev()```

This returns a single value, which will be the standard deviation of the data.

## Plotting Data

We can plot our data by simply calling the function:

```plot_bar()```

This function does not return any value and plots the bar chart of the data
(either sample or dataset).

## Caluclating Probibility Density Function (PDF)

PDF is an important property of a data set. We can calculate it by:

```PDF = pdf(k)```

Where **k** is the point where PDF needs to be found.

## Plotting the pdf

We can also visualise and plot the pdf calculated for the data.
We can make use of the function:

```plot_bar_pdf()```

## Adding two Binomial objects

Adding two binomial objects is not as simple as *a+b*.
Properties and size changes.
However, using this lbrary, any instances of Binomial can be added together
as simply as B! + B2, where B1 and B2 are the Binomial objects.

```B1 + B2```

## Viewing Objects

To quickly view the object details, just type *object* in the IPython and its
important details will be made visible.
