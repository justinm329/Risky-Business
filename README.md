# Risky-Business-

## Overview

* Build and evaluate several machine learning models to predict credit risk using data you'd typically see from peer-to-peer lending services. Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans), so I will employ different techniques for training and evaluating models with imbalanced classes. I will use the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques:
   1) Resampling
   2) Ensemble learning 

## Credit Ensemble Questions

* Which model had the best balanced accuracy score?

   The Easy Ensemble Classifer out performed the Balanced Random forecast Classifer. The easy ensemlbe had a score of 0.93 and the random Forecast had a socre of 0.77

* Which model had the best recall score?

   The Easy Ensemble had the better recall score between the two.

* Which model had the best geometric mean score?

   The Easy Ensemble had the better geometric mean score between the two.

* What are the top three features?

  The top three features were:

    1) total_rec_prncp : (0.06862801182224613)

    2) total_rec_int : (0.06038649619780159)
    
    3) total_pymnt : (0.05905244774386602)
    
## Credit Resample Questions

* Which model had the best balanced accuracy score?
  
  The SMOTE and Random Over Sampling model has the best balanced accuracy score.

* Which model had the best recall score?

  All the models had the same score of .99 for recall.

* Which model had the best geometric mean score?

  All the models had the same score of .99 for geometric mean.
