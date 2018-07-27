[![HitCount](http://hits.dwyl.io/susantabiswas/stackoverflow-question-tagger.svg)](http://hits.dwyl.io/susantabiswas/stackoverflow-question-tagger)
# <u>StackOverflow Question Tagger
StackOverflow lets the users to post their queries and the other users can help them with answers. The site uses tags for managing the questions effectively. Here we will be predicting tags for a given question. Tags like C, C++, Python are widely used.

This model can predict appropriate topic tags for a variety of StackOverflow questions.

## Model Performance: 
### 1. Using Bag of Words

![bow1](media/bow1.JPG)
![bow2](media/bow2.JPG)

### 2. Using TF-IDF
![tfidf1](media/tfidf1.JPG)
![tfidf2](media/tfidf2.JPG)

As you can see there are some instances when the prediction made using TF-IDF gives us no meaningful result, instead gives us a blank result. This problem can be solved by hyperparameter tuning, thereby increasing the model accuracy for unseen data. The above model uses SVM Linear classifier by the way.

### References
Inspired by this course https://www.coursera.org/learn/language-processing
