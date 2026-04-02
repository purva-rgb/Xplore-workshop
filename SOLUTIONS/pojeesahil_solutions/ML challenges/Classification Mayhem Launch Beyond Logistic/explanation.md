## My Approach 
Initially, I tried to visualize the data using matplotlib and making scatter plot
pattern was zigzag,I knew log Regression would definitely not work, so first i decided to go with **SVC**(binary nonlinear classifier), implementing it got me only 64.7% accuracy even after fine tuning it ,i could not go higher than 85% so i decided to go with Random Forest Classifier which gave me 93.9% accuracy, after this, I also checked **k Nearest Neighbour** algorithm however it gave 92.7% accuracy which was worse than Random forest Classifer so i decided to settle on **Random forest Classifier** only

**Accuracy Score: 0.939**

---
### Classification Report:
---
|  | percision | recall | f1-score | support|
|--|--|--|--|--|--|
|0|0.92|0.92|0.92|382|
| 1 | 0.95 |0.95|0.95|618|
|accuracy| | |0.94|1000|
| micro avg | 0.94 |0.93|0.94|1000|
| weighted avg | 0.94 |0.94|0.94|1000|


         
