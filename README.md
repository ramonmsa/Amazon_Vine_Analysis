# Amazon Vine Analysis
## Purpose
To determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Resource
This analysis uses the following Resources:
-   Data Source: *__amazon_reviews_us_Books_v1_00.tvs.gz__*
-   Notebook: *__Google Colab__*
-   Library: *__PySpark__*

## Results
The analysis helps us to answer the following questions:

- How many Vine reviews and non-Vine reviews were there?
	- It shows that the dataset contains the total of *__5012__* __Vine reviews__ and  the number of *__109297__* __non-Vine reviews__.
	
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
	- It noticed that *__2031__* of the __Vine users__ reviewed __5 stars__.
	- And that *__49967__* of the __non-Vine users__ reviewed __5 stars__. 
	
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 starts?
	- Therefore, the total number of Vine 5 stars reviews represents *__41%__* of the total of Vine reviews.
	- When the total of Non-Vine 5 stars reviews represents *__46%__* of  the non-Vine total reviews.

![image](https://user-images.githubusercontent.com/69650068/137570003-16e77d34-c0b0-4479-8a67-44c70c3ff30f.png)
<br />*The image above shows the results of the analysis made based on the dataset.*


## Summary
Considering that both Vine 5 stars reviews and non-Vine 5 stars reviews express 41% and 46% of the total reviews respectively, it is possible to assume that remaining reviews percentage is distributed among four, three, two, 1 and 0 stars. Even if this distribution is not even, the 5 stars reviews most probably correspond to the majority of the reviews. 

Consequently, these numbers and assumption let us detect a bias toward favorable reviews.

However, in order to support this statement, it would be auspicious to consider filtering the dataset by the total number and percentage for each of the stars reviews.
