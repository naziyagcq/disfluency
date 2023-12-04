# disfluency
shared task related documnts
This repository shares the code for shared task by team Diya.
We have achieved the multiclass classification using a code-mixed mode with hyper parameter tuning.
Our results on validation dataset Classwise are shown below:
classifiation report
              precision    recall  f1-score   support

  B-repeat_R       0.00      0.00      0.00         0
B-Alteration       0.00      0.00      0.00         0
           O       1.00      0.92      0.96      7197
   B-false_R       0.00      0.00      0.00         0
   I-false_R       0.00      0.00      0.00         0
    B-edit_R       0.25      1.00      0.40         8
    I-edit_R       0.14      1.00      0.25         3
     B-pet_R       0.81      0.89      0.85        95
  B-filler_R       1.00      0.89      0.94       178
  B-repair_R       0.00      0.00      0.00         0
  I-repair_R       0.32      0.42      0.36        59
  I-repeat_R       0.00      0.00      0.00         0
I-Alteration       0.00      0.00      0.00         0
     I-pet_R       0.20      0.20      0.20         5

    accuracy                           0.92      7545
   macro avg       0.27      0.38      0.28      7545
weighted avg       0.99      0.92      0.95      7545

Other reports and loss function variations are shown through charts in the google colab notebook as a clear output below the code itself. 

Other
