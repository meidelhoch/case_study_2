Case Study Project for Statistical Learning (Stat 270) at Carleton College
By Marc Eidelhoch and Piper Dean

This is a Quadratic Discriminant Analysis (QDA) model that uses handwriting data from the MINST dataset to predict whether a given digit is a 6 or a 7.

We created one "mask" of points (six_region.csv) that contains the points that are most common among 6's in our training data and another "mask" of points (seven_region.csv) that contains the points that are most common among 7's in our training data. Then, for a given digit, we calculate the percentage of points that are covered by each mask and use that to calculate predict whether the given digit is a 6 or a 7.

We achieved 98.9% test accuracy which suggests we have a very good model.

A PDF of the final written report is also included in this repository called final_report.pdf.
