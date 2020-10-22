 # accuracy comparison of parkinson's Disease Detection  before and after feature selection

## problem statement 
   
   compare the accuracy  of parkinson's Disease Detection before and after feature selection
   
## data cleaning :
          remove noisy  points 
          fill empty cells  with reasonable values  .
          
## feature selection methods used :

  1)RFE Recursive feature elemination 
  
  2) select from model feature selection 
      
## machine learning algorithms used :

  ###  1) Random Forest Classifier
  ###  2) SVM
  ###  3) Guassian NB 
  ###  4) Logistic Regression
  
  
  ## Data set 
       
      --> the data set is created by voice features .
      --> data set is taken by kaggle , it has 195 rows and 24 columns. and which is  imbalanced data set .
  
  
  
  
  ##  before feature selection :
  
                                       
                                       the accuracies are :
                                       
                                                      "svm"                   ---->     0.8358974358974359,
                                                                                   
                                                      "RandomForest "         ---->      0.841025641025641
                                                      
                                                      "LogisticRegression"    ---->     0.8358974358974359
                                                      
                                                      "GaussianNB"            ---->    0.6974358974358974
                                       
                                       
                                       
                                       
   ##  afetr  RFE feature selection :
  
                                       
                                       the accuracies are :
                                       
                                                      "svm"                   ---->      0.8507692307692308
                                                                                   
                                                      "RandomForest "         ---->       0.8974358974358975
                                                      
                                                      "LogisticRegression"    ---->       0.8458974358974359
                                                      
                                                      "GaussianNB"            ---->        0.7846153846153846                                    
                                       
                                       
                                       
                                       
                                       
# conclusion :

                   after feature selection accuracy improvement is  little bit for the models SVM , Logistic Regression , Guassian NB  .
                   
                   but the  improvement of the accuracy in randomforest classifier is more than other models. 
 
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
                                       
              
                                       
                                       
                                       
                                       
