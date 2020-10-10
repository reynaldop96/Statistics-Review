# Statistics-Review
Review of some statistics concepts

## Curse of Dimensionality

The curse of dimensionality makes data points appear similar to each other as the number of dimensions goes up. In order to achieve statistical significance, it is necessary to increase the number of data points exponentially. In this notebook, I generate 98 data sets with 10,000 rows each, with columns increasing from 2 to 100. Then, I take the differene between all points within a data set, and then take the standard deviation of the differences in order to measure the spread of differences. In theory, the curse of dimensionality would imply that the standard deviation between all data points decreases as the number of dimensions increases, since the points become "closer" to each other. This is exactly what happens: standard deviation decreases as the number of variables increases, reaching what seems is  a certain threshold. 
