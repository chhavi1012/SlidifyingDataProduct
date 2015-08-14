slidifying Data Product
========================================================
author: chhavi agrawal
date: 08/14/2015


========================================================

##Description

The Shiny App I wrote displays energy consumption information:

. gas

. electricity

. water

for the years 2012 to 2014.

========================================================
##Details

These data are diffed, week by week, so that I get the week's consumption.

Further more, a formula is applied to compute an estimate price (expressed in EUR) for the week's consumption.

========================================================

##Example

Here are the first 5 lines of the Excel file (for the columns which interest me, the ones I show in the barplot):



```r
data <- read.csv("consumption.csv", sep=",", header=T)

subset(data,select=c(Date,PriceGas,PriceElec,PriceWater))[1:5, ]
```

```
        Date PriceGas PriceElec PriceWater
1 2012-01-01    55.51     22.14       2.96
2 2012-01-08    57.22     23.67       3.30
3 2012-01-15    62.07     23.29       3.26
4 2012-01-22    56.59     23.67       3.02
5 2012-01-29    63.63     23.86       3.12
```

========================================================

##Conclusion:-

data visualization is very important part of data analysis ,shiny is amazing R package ,  enables R programmer to create interactive web application and moreover capability to share with technical and non technical audience.
