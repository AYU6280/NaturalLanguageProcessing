This is a model trained on randomforest to classify if a message is spam or not. 
using tfidfvectorisation, pyforest, sklearn. 
Accuracy: 
0.9420935412026726

confusion matrix: 
array([[214,   3],
       			[ 23, 209]])


classification report:
 
precision    recall  f1-score   support

         ham       0.90      0.99      0.94       217
        spam       0.99      0.90      0.94       232

    accuracy                           0.94       449
   macro avg       0.94      0.94      0.94       449
weighted avg       0.95      0.94      0.94       449
