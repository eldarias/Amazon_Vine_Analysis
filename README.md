# Amazon_Vine_Analysis
Module 16: Big Data

---
## Overview
The purpose of this challenge was to pick one of the many available Amazon Vine program datasets and use PySpark to perform the ETL process to extract the dataset, transform the data and connect to an AWS RDS **Postgres** instance.  Finally, PySpark was used to determine if any bias was found toward favorable reviews from Vine members in the selected dataset.

---

## Results:
Below are the results based on the outputs after the data was filtered as requested:

- How many Vine reviews and non-Vine reviews were there?
    - <image src="./Results/Total_Vine_vs_NonVine_Reviews.PNG">
    - From the above results, we can see **"0"** reviews by Vine members and **"129,516"** reviews by non-Vine members.
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    - <image src="./Results/5-Star_Vine_vs_NonVine_Reviews.PNG">
    - Per the above output, there were **"0"** 5-Star reviews by Vine members and **"59,278"** 5-Star reviews by non-Vine members.
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
    - <image src="./Results/TotalCount_PercentageByMembership.PNG">
    - From the above output we can see that **0%** of the total 5-Star reviews were by Vine Members and **100%** by Non-Vine members.

---

## Summary:
In summary, no conclusions can be drawn regarding positive bias for reviews in the Vine program since the dataset did not include any reviews by Vine Members.  The dataset pre-filtering was verified and confirmed that there were also no reviews by Vine members therefore a different dataset should be analyzed or a new dataset should be provided that includes reviews from Vine members.