# Playstore App Analysis

<p align="center">
  <img src="./Images/Google PLAYSTORE APP.png">
</p>

Contributors
---
* @kishchoy 
* @jneoh001 
* @RAMTEJ001

About
---
This is our group's project that we have done for module SC1015 Introduction to Data Science and Artifical Intelligence. 

We will be analysing a dataset with a size of approiximately `2 million` data.

Dataset Obtained from:  https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps

Problem Defintion
---

Upon glancing at this dataset, we were interested in what we could discover from the data about Google Play Store Apps. Specifically, we wondered if there there was a ''formula'' for success for apps in the Play Store. Also, we were very curious on whether success could be predicted based on certain data.

Therefore, we came up with the following 2 main questions that would help guide us.

1. Figure out what are the most important factors for an app to be successful in the Google Play Store?
2. Are we able to predict the number of installs based on app info/reviews?


Models Used
---
1. Classification Tree
2. Multi Linear Regression 
3. XGBoost



What we have learnt/utilized BEYOND this course
---
* F1 Score
* XGBoost
* One-Hot Encoding
* Multi Linear Regression





<p align="center" style="background-color:powderblue;"> XGBoost </p>
<p align ="center">
  <img src="./Images/XGBoost_logo.png">
</p>

Individual Contributions :)
---
* @kishchoy - EDA, EDA Analysis, Machine Learning
* @jneoh001 - EDA, EDA Analysis, Machine Learning
* @RAMTEJ001 - EDA, Machine Learning, Conclusion


Conclusion and Reflection
---

We had originally narrowed some factors determining success in our EDA from our analysis. Afterwards, we tried to predict number of installs using Classification Tree but that did not work out well as it had a low accuracy of about `0.31`.

We proceeded to then try Multi Linear Regression (MLR) Model to improve prediction by trying out another model to see if that would work, but to no avail because it also had a low accuracy as its Explained Variance was low at `0.29`.

Although none of the models was able to determine an attribute that was able to predict the number of installs well, we tried to increase the accuracy by reducing the number of attributes that we dealt with , filtering and cleaning the data.

Lastly, we then used XGBoost to narrow down the most important factors that influence installs.

---

In conclusion, to reiterate our answer to the questions.

Q1 - More important factors are `Price`, `Content Rating` and `Rating Count`.

Q2 - Unfortunately, we are unable to make a model that can accurately predict installs based on app info.

We feel that more data is needed to accurately predict installs. We feel that the dataset is currently insufficient to do so.

Given more valuable data in relation to Minimum Installs, such as Marketing budget for the app, we feel that this can improve the accuracy of prediction as data like this is more valuable. 

Overall, this was a very interesting dataset and we gained a lot of insight after analysing it.





References
---


- Scikit-learn: Machine Learning in Python, Pedregosa et al., JMLR 12, pp. 2825-2830, 2011.
- https://xgboost.readthedocs.io/en/stable/ 
- https://www.educative.io/edpresso/what-is-the-f1-score
- https://seaborn.pydata.org/index.html
- https://towardsdatascience.com/jupyter-and-markdown-cbc1f0ea6406
- https://deepai.org/machine-learning-glossary-and-terms/f-score
- https://www.geeksforgeeks.org/adding-new-column-to-existing-dataframe-in-pandas/
- https://medium.com/machine-learning-with-python/multiple-linear-regression-implementation-in-python-2de9b303fc0c
- https://www.statology.org/one-hot-encoding-in-python/
- https://www.datacamp.com/community/tutorials/xgboost-in-python
