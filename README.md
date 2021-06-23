# Tag-Persian-Entities-Using-Bert
Thanks to https://github.com/hooshvare/hooshvare.github.io I built a fa-bert model for tagging persian entities in sentences.
<br>I suggest that you read https://arxiv.org/abs/1801.09936 before using this code. (Main reference)
> Accuracy for each label:
>               precision    recall  f1-score   support

       B_DAT       0.50      0.25      0.33         4
       B_LOC       0.67      0.50      0.57         4
       B_MON       1.00      0.25      0.40         4
       B_ORG       0.80      1.00      0.89         4
       B_PCT       0.36      1.00      0.53         4
       B_PER       0.42      1.00      0.59         5
       B_TIM       0.80      1.00      0.89         4
       I_DAT       0.50      0.25      0.33         4
       I_LOC       0.50      0.25      0.33         4
       I_MON       1.00      0.25      0.40         4
       I_ORG       1.00      0.25      0.40         4
       I_PCT       1.00      1.00      1.00         5
       I_PER       1.00      0.25      0.40         4
       I_TIM       0.60      0.75      0.67         4
           O       0.67      1.00      0.80         4

    accuracy                           0.61        62
   macro avg       0.72      0.60      0.57        62
weighted avg       0.72      0.61      0.58        62
