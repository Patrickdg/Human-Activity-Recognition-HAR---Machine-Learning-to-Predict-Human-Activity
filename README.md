# Human Activity Recognition (HAR) - Machine Learning to Predict Human Activity

This project was completed as part of the Practical Machine Learning course offered by Johns Hopkins University through Coursera.  

The final rendered submission of this project can be found [here](https://patrickdg.github.io/Practical-Machine-Learning-Project/).  

# Data Source and Accompanying Research
[Groupware@LES](http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har#sbia_paper_section)  
[Wearable Computing: Accelerometers’ Data
Classification of Body Postures and Movements](http://web.archive.org/web/20170519051609/http://groupware.les.inf.puc-rio.br/public/papers/2012.Ugulino.WearableComputing.HAR.Classifier.RIBBON.pdf)  
[Qualitative Activity Recognition of Weight Lifting Exercises](http://web.archive.org/web/20170519033209/http://groupware.les.inf.puc-rio.br/public/papers/2013.Velloso.QAR-WLE.pdf)  
[Dataset](http://web.archive.org/web/20161224072740/http://groupware.les.inf.puc-rio.br/static/WLE/WearableComputing_weight_lifting_exercises_biceps_curl_variations.csv)  

## Synopsis
An analysis was conducted and a prediction model of the Human Activity Recognition (HAR) data . After loading, cleaning, and preprocessing the data with *Principal Components Analysis (PCA)*, 3 models were fitted to test accuracy of prediction: *random forests (rf), boosting (gbm), and linear discriminant analysis (lda)*.  

The **random forests model showed the highest accuracy rate at 0.9750 accuracy with an interval in the range [0.9707, 0.9789]**. Cross-validation methods were set as ‘cv’ across all models for simplicity in computations, and PCA was performed in order to consolidate the large number of predictors in the original dataset.  
