# Amazon Vine Analysis

## Overview of the analysis: 
The purpose of this project is to analyze Amazone written reviews by members of the Vine program, and determine if there is any bias in product reviews depending on whether the reviewers were paid or not.

## Results: 
- **After filtering** the data for rows where the **total_votes** count is *greater or equal 20*:
    - There were a total of 27389 reviews
    - 12371 of the total reviews were 5-star reviews
    - 202 of the five-star reviews were vine (paid) reviews
    - 12033 of the five-star reviews were non-vine (unpaid) reviews
    
| total      | five-stars | vine  | non-vine |
|------------|------------|-------| ---------|
| 27389      | 12371      | 202   | 12033    |

## Summary: 
The number of 5-star reviews from the vine program constitutes about 1.6% of the total five-star reviews. Based on this result I conclude that the paid vine progam has *no postive bias* in product reviews.
