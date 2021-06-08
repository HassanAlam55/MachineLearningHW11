# Summary of Machine Learning & Classifiction Homework:
1. [Overall](#Overall)
2. [Resampling](#Resampling)
3. [Ensemble Learning](#Ensemble-Learning)

#### Overall 
Accoding the tests I ran, there did not much difference between the different models for  <span style="color: blue;">*these datasets*</span>. Summary for each section below:

#### Resampling 
[link to resampling notebook](credit_risk_resampling.ipynb)
1. Which model had the best balanced accuracy score?
   : *all models seem to give similar results*
2. Which model had the best recall score?
   : *Naive, SMOTE and Combined give best scores by a very small margin.*
3. Which model had the best geometric mean score?
    : *all give the same results*
    

#### Ensemble 
[link to ensemble notebook](credit_risk_ensemblev.ipynb)
1. Which model had the best balanced accuracy score?
    : *easy ensemble has a higer f1 by a small margin*
2. Which model had the best recall score?
    : *easy ensemble has a higher score by a small margin*
3. Which model had the best geometric mean score?
   .: *easy ensemble has a higher score by a substantial margin (0.93 vs 0.74)*
4. What are the top three features?
   : *total_rec_prncp, last_pymnt_amnt, total_pymnt_inv*
