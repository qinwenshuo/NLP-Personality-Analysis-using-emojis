# NLP-Personality-Analysis-using-emojis

Goal: To determine whether emojis appeared in online communications are reliable predictors of one's personality.

Personality analysis with internet user posts has widely been used to predict personality type and psychological research. Cui et al.(2017) evaluated 
the classification accuracies of the MBTI personality type with Naive Bayes, SVM, and DNN. Their dataset provides 45-50 most recent social media posts of 
8600 users with the users’ MBTI personality type from the online forum PersonalityCafe. The authors compared 4 binary classifications (i.e. E/I, S/N, 
T/F, J/P) with the 16-class classification using Naive Bayes, SVM, and DNN algorithms. They found that 16-class classification achieves accuracy lower 
than 50%, while binary classification can achieve accuracy higher than 60% for all three models. Their work greatly inspired our project. They use bags 
of words as semantic representation, which we believe can be replaced and the representation can be enhanced by Google's word2vec model. Moreover, they 
did not compare the latest BERT model performance on the personality classification task with other machine learning algorithms. In addition, their pre-
processing of posts removes a lot of meaningful semantic information, such as emojis, which we believe significantly reduces the amount of information in 
posts that could be potentially useful for personality prediction. Continuing on this idea, we want to test whether emojis can be important indicators of 
personality.

