# Part C — Questions, Assumptions & Contradictions

## 1. Questions
1- Can employees work at multiple branches? (SRS 7.2)
2- Can reservation result in more than one rental? (SRS 7.11–7.12)
3- Can rental have multiple insurance packages? (SRS 7.13)

## 2. Assumptions
1- each employee belongs to one branch at a time (SRS 7.2)
2- each reservation can create only one rental (SRS 7.12)
3- additional drivers must be authorized drivers of the same corporate customer (SRS 7.12)

## 3. Contradictions
No explicit



# Part D — Business Rules Beyond Constraints
customers cannot redeem more points than their available balance
  >>>>>> requires calculating total points.

corporate rental drivers must belong to the same company as the rental customer.
 >>>>>> requires checking related records

 A corporate rental's main driver and additional drivers must be authorized drivers belonging to the same corporate customer who owns the rental
 >>>>>> this requires that the driver and rental belong to the same corporate customer across related records