# "Amazon_Vine_analysis" Week 16 Challenge
## Overview
Different natural language processing skills were used to perform ETL on Amazon.com review data for a client interested in video games.

## Results
### How many Vine reviews and non-Vine reviews were there?
The dataset had a total of 145,431 reviews. Though, only reviews with 20 or more votes where considered leaving 3,342 reviews to analyze. Helpful votes were defined as being 50% or greater than the total votes narrowing the list to 1,685 reviews. Due to the applied criteria it, unfortunately, significantly diminished the sample size. In the remainder 1,685 reviews, there were no reviews that were paid for by the Vine program.
![no_paid-for](https://github.com/rudiferr/Amazon_Vine_analysis/blob/main/images/no_paid-for.png?raw=true)

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
As for 5-star unpaid Vine reviews, there were 631 reviews. Attempting to divide by zero, the code would result in a zero division error. Therefore, there are also 0 paid Vine with 5-star reviews.

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
The percentage of unpaid, 5-star Vine reviews resulted in 37.4%, while the percentage of paid, 5-star Vine reviews would be 0%.
![unpaid_perc](https://github.com/rudiferr/Amazon_Vine_analysis/blob/main/images/unpaid_perc.png?raw=true)

## Summary
Because the sample size was constricted to a degree that it was impossible to compare paid and unpaid Vine reviews, the analysis is biased towards unpaid Vine reviews. Another indicator is comparing 37% of unpaid, 5-star Vine reviews to 0% paid, 5-star Vine reviews also shows that the unpaid Vine are biased as well.

The starting criteria of 20 likes or the 50% helpful criteria may have been too high, which made the data set too small. Adjustments to these criteria is a first step to reconsidering using this data set.