# Importing

We can simply import the class by typing:

```from EasyStatistics import Gaussian```

This will make the class avalable for you.

## Creating objects

We can quickly create Gaussian distribution objects by typing:

```G1 = Gaussian(mean, std)```

Here, **mean** and **std** are the mean and standard deviaton of the data.

This will create an object G1 for us, which has Gaussian distribution.

## Calculate mean

We can easily calculate the mean of our data by using the function:

```Mean = calculate_mean()```

It returns a value which is the mean of the data.

## Calculate Standard Deviation

Standard deviation is an important parameter of any normal distribution. We can
calculate standard deviation by typing:

```STD = calculate_stdev(True/False)```

Here, **True** means that the data is a sample.

## Plotting Data

We can plot a histogram of our data using the following functon:

```plot_histogram()```

This function returns nothing, but simply plots and prints the data on a histogram.

## Calculating Probibility Distribution Function (PDF)

PDF can be calculated using:

```PDF = pdf(x)```

Where x is the point where PDF needs to be found.

## Plotting PDF

It is always a good option to be able to print the PDF calculated of the data.

```X, Y = plot_histogram_pdf(n_spaces)```

Here:

* X, Y are a list of the points on x and y axis respectively.
* n_spaces is the parameter of how many points x-axis should have.

## Addng two Gaussian objects

Adding two gaussian distribution is not as simple as adding two numbers.

The resulting gaussian object has different values and properties.

However, using this package, we can simply add two gaussian objects as:

```G_result = G1 + G2```

This creates a new object *G_result* with resulting properties.

## Viewing an object

The necessary details of a gaussian object can be viewed by simply typing
G1 in IPythn shell, and all the important details will be displayed.
