# P&S Lab Assignment 1: Naive Bayes Classifier

## Task
Determine which class - fake or credible - some observation probably belongs to by using the Bayes formula.

Dataset - fake news

## Algorithm
Steps taken to perform the task :
- Analyze the dataset, process it to turn into a bag-of-words
- Use Bayes' formula to try to predict the class of a message.
  - Calculate the probability for the bag-of-word to be in fake class.
  - Calculate the probability for the bag-of-word to be in credible class
  - Compare them.
- Compute the success of the predictions

## Statistics and summary
Accuracy : approximately 93% (0.9289 out of 1)

![image](https://user-images.githubusercontent.com/67468470/196503653-9ff758f4-157b-48e4-88fc-8eee3922fcda.png)

Pros of using Naive Bayes approach :
  - Simple to implement
  - Comparatively fast by the assumption that the features are independent.

Cons :
   - Does not work for non-independent features.
 
 In the dataset given, we assumed that there was no correlation between the word frequency and our method still had
 good results. However, it could be a good practise e.g to consider the dependencies of the word appearance.

## License

The [MIT](https://choosealicense.com/licenses/mit/) License (MIT)

Copyright © 2022. Andrii Yaroshevych, Dmytro Vasylkiv, Vitalii Petrychko

