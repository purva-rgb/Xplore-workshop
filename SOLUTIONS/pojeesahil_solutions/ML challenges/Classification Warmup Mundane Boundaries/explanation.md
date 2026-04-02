## My Approach 
First, I tried to visualize the data using matplotlib and making scatter plot
It almost look like it could be divided by single boundary and looking at dataset I got to know result was binary, so first i decided to go with **log Regression**(binary linear classifier), implementing it got me 95% accuracy then i notice that scatterplot is not exactly linear, there are some curves too so i decided to go with non linear classifier, random forest classifier gave 96% accuracy while SVC gave me 98% accuracy so i settled down with **SVC**.

**Accuracy Score: 0.98**

---
### Classification Report:
---

|  | percision | recall | f1-score | support|
|--|--|--|--|--|--|
|0|0.97|1.00|0.98|57|
| 1 | 1.00 |0.95|0.98|43|
|accuracy| | |0.98|100|
| micro avg | 0.98 |0.98|0.98|100|
| weighted avg | 0.98 |0.98|0.98|100|


         
