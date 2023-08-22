# shift_test_job

 Test Task for the CFT.ru.
 The purpose is binary classification whether client pays his loan or not.

There was 10 questions and the answer is in main.ipynb. After that there was a competition.
Purpose of the competition is to reach highest result with metric Gini = 2 * ROC_AUC - 1.

My final result is 47 place from 199 with Gini = 0.4632. 
That result was reached via catboost model tuned with Optuna.
