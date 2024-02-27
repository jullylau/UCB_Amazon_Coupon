# Amazon Location Coupon Data Analysis Report
Using survey data from Amazon Mechanical Turk, this analysis provide insight into what type of customer under what circumstances are more likely to accept certain type of coupons

## Data Description
Data collected on location coupons offered to drivers and whether coupons were accpted

### User attributes
-  Gender: male, female
-  Age: below 21, 21 to 25, 26 to 30, etc.
-  Marital Status: single, married partner, unmarried partner, or widowed
-  Number of children: 0, 1, or more than 1
-  Education: high school, bachelors degree, associates degree, or graduate degree
-  Occupation: architecture & engineering, business & financial, etc.
-  Annual income: less than \$12500, \$12500 - \$24999, \$25000 - \$37499, etc.
-  Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
-  Number of times that he/she buys takeaway food: 0, less than 1, 1 to 3, 4 to 8 or greater
than 8
-  Number of times that he/she goes to a coffee house: 0, less than 1, 1 to 3, 4 to 8 or
greater than 8
-  Number of times that he/she eats at a restaurant with average expense less than \\$20 per
person: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
-  Number of times that he/she eats at a restaurant with average expense between $20 to $50 per
person: 0, less than 1, 1 to 3, 4 to 8 or greater than 8

### Contextual attributes
- Driving destination: home, work, or no urgent destination
- Location of user, coupon and destination: we provide a map to show the geographical
location of the user, destination, and the venue, and we mark the distance between each
two places with time of driving. The user can see whether the venue is in the same
direction as the destination.
- Weather: sunny, rainy, or snowy
- Temperature: 30F, 55F, or 80F
- Time: 7AM, 10AM, 2PM, 6PM, or 10PM
- Passenger: alone, partner, kid(s), or friend(s)
- Type of car

### Coupon attributes
- Time before it expires: 2 hours or one day

### Result
- Coupon was accepted or rejected

## Data Set
- Number of records: 12,684
- Missing data
  - Type of car data missing for majority of the records
  - Frequency for going to bar, coffee house, restaurants and getting takeout are missing 1-2% of the records  

Data file: [coupons.csv](data/coupons.csv)
