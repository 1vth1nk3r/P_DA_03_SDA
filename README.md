# Telecom plans analysis
The project from the Statistical Data Analysis sprint of the Practicum DA/DS course.

## Description
Here we have a small dataset of various data on a telecom company's clients. We would like to know if one of the prepaid plans (Surf and Ultimate) brings in more revenue.

First, we should do some data preprocessing: fill in the missing values, clean spelling errors, and change data types. Also, we need to add some new columns to help our analysis. After doing so, we could explore our data and test hypotheses. 

## Conclusion
After preprocessing, I aggregated monthly usages of call minutes, messages, and data for each user. These sums let me calculate the users' monthly revenue.

The distributions of used minutes, messages and data volumes don't differ much between users of different plans. Thus, both groups of customers behave similarly.

I tested if the average revenues from the Ultimate and Surf plans are equal. The test showed a significant difference between average revenues, and the **Ultimate** plan brings in *more revenue*.

Also, I compared the data from users in the NY-NJ area and all other places combined. The test showed a significant difference between average revenues in these areas.
