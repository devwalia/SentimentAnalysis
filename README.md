# SentimentAnalysis
SENTIMENT ANALYSIS MODEL ON SOCIAL MEDIA (TWITTER DATA)

n this project, we try to implement a Twitter sentiment analysis model that helps to overcome the challenges of identifying the sentiments of the tweets. The necessary details regarding the dataset are:
·      The dataset provided is the Sentiment140 Dataset which consists of 1,600,000 tweets that have been extracted using the Twitter API. The various columns present in the dataset are:
o   target: the polarity of the tweet (positive or negative)
o   ids: Unique id of the tweet
o   date: the date of the tweet
o   flag: It refers to the query. If no such query exists then it is “NO QUERY”
o   user: It refers to the name of the user that tweeted
o   text: It refers to the text of the tweet

 
RESULTS-


<img width="581" alt="image" src="https://user-images.githubusercontent.com/58397422/162613219-54472193-a5c7-4ae6-b9a0-f6ae172a8d05.png">
<img width="465" alt="image" src="https://user-images.githubusercontent.com/58397422/162613226-755ef3ce-5d63-42e2-9eae-cb11cfccf581.png">
<img width="281" alt="image" src="https://user-images.githubusercontent.com/58397422/162613234-7ae66691-5600-40bb-8bbd-c3ce9a507d17.png">
<img width="450" alt="image" src="https://user-images.githubusercontent.com/58397422/162613255-6f0b88b6-4488-49e3-b021-2a6521ea242d.png">
<img width="450" alt="image" src="https://user-images.githubusercontent.com/58397422/162613259-1acd74d4-7510-4c83-aba0-40915d6380a5.png">
<img width="250" alt="image" src="https://user-images.githubusercontent.com/58397422/162613266-56df6194-aded-4b8e-87f3-e1b24fd36736.png">
<img width="280" alt="image" src="https://user-images.githubusercontent.com/58397422/162613269-49932d0a-4b79-4d15-b8fd-ab3c655255d7.png">
<img width="198" alt="image" src="https://user-images.githubusercontent.com/58397422/162613278-41dde58d-21bf-4d9c-9038-d1259f3addff.png">
<img width="277" alt="image" src="https://user-images.githubusercontent.com/58397422/162613282-8f9a8a8a-b1ea-47bc-8115-01ddcf9250c1.png">
<img width="221" alt="image" src="https://user-images.githubusercontent.com/58397422/162613286-b0254cda-451e-4993-86c8-f4662e7d8292.png">
<img width="283" alt="image" src="https://user-images.githubusercontent.com/58397422/162613289-70647b73-86ec-4cae-aaa9-2e7cc8c7317f.png">




 
Conclusion

Upon evaluating all the models we can conclude the following details i.e.
Accuracy: As far as the accuracy of the model is concerned Logistic Regression performs better than SVM which in turn performs better than Bernoulli Naive Bayes.
F1-score: The F1 Scores for class 0 and class 1 are :
(a) For class 0: Bernoulli Naive Bayes(accuracy = 0.90) < SVM (accuracy =0.91) < Logistic Regression (accuracy = 0.92)
(b) For class 1: Bernoulli Naive Bayes (accuracy = 0.66) < SVM (accuracy = 0.68) < Logistic Regression (accuracy = 0.69)
AUC Score: All three models have the same ROC-AUC score.
We, therefore, conclude that the Logistic Regression is the best model for the above-given dataset.
In our problem statement, Logistic Regression is following the principle of Occam’s Razor which defines that for a particular problem statement if the data has no assumption, then the simplest model works the best. Since our dataset does not have any assumptions and Logistic Regression is a simple model, therefore the concept holds true for the above-mentioned dataset.
 
 
REFERENCES –
https://monkeylearn.com/sentiment-analysis/
https://techvidvan.com/tutorials/python-sentiment-analysis/
https://www.geeksforgeeks.org/twitter-sentiment-analysis-using-python/

