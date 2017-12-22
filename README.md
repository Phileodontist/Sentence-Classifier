# Sentence-Classifier
**COGS 109: Modeling and Data Analysis (Final Project)**

The following jupyter notebook contains code to the preprocessing step of this project.

**Preprocessing:**
1) Retrieving desired text files from directory
2) Removing desired stop-words from NLTK's list of stop-words
3) Sentence segmentation + removing stop-words + lowercasing
4) Storing sentences and labels into a Dataframe
               
# UPDATE
Due to having a small training set relative to the testing set, we weren't able to continue with our project with this data set. This was the case since only a handful of sentences were actually tagged (training), whereas a large amount of the other sentences weren't (testing).

Alternatively, we decided to implement a text classifier by modeling a Multinomial Naive Bayes classifer as well as a SVM classifier, using the 20newsgroup data set.

Please refer to the [Text-Classifier](https://github.com/Phileodontist/Text-Classifier) repository.
