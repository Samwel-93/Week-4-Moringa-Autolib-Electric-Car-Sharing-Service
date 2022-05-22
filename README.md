# Week-4-Moringa-Autolib-Electric-Car-Sharing-Service
**Project Background**

Working as a Data Scientist for the Autolib electric car-sharing service company to investigate a claim about the blue cars from the provided Autolib dataset.

An example of claim to test would be; 
> "Is the number of Bluecars taken in area X different than in area Y? Is it greater in area X than in area Z? Etc”. 

>*The selected periods of interest be either weekdays or weekends but not a mix of both. You can also consider postal codes 75015 vs 75017 to some of the areas of interest.*

To work on this project, we will perform the following analysis with Python; 

1. Find and deal with outliers, anomalies, and missing data within the dataset.
2. Plot appropriate univariate and bivariate summaries recording our observations.
3. Implement the solution by performing hypothesis testing.

The dataset to use for this project can be found here "http://bit.ly/DSCoreAutolibDataset"

> The provided dataset is a daily aggregation, by date and postal code, of the number of events on the Autolib network (car-sharing and recharging).

**Hypothesis**

The Data scientist claims that at any given period the number of blue cars taken from stattion 75015 has no difference with number of blue cars taken fro stattion 75017

*Null hypothesis:* The number of blue cars taken from station 75015 on equal to the number of blue cars taken from station 75017.

*Alternative hypothesis:* There is a difference between the number of blue cars taken from station 75015 and number of blue cars taken from station 75017.

> ma = number of blue cars taken from station 75015

> mu = number of blue cars taken from station 75017


Ho: ma = mu

H1: ma ≠ mu (Claim)
