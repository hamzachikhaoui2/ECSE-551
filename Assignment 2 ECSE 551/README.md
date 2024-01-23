
# ECSE 551 Assignment 2 description

Hamza Chikhaoui 260912960
Aymen Boustani 260913311

The following project is articulated around the following documents :
 - The Analysis Final file, that contains all the informations about data processing (how many samples per class amongst others.)
    - The Analysis Final file also contains the implementation of all the models we have considered for this assignment  : 
        - The Naive Bayes model coded from scratch
        - a Decision Tree classifier
        - a Logistic Regression classifier
        - a LDA classifier
        - a KNN classifier
        - classifiers implementing stacking and boosting
    
- The Analysis Main file, that contains some of the same models, but optimized differently.

Both models are submitted to the results obtained from different rounds of optimization that was done for this project.
It is also important to note that the highest values of accuracies and other most important results from both files can be found in the final submission for this assignment, available on mycourses.




About the Analysis Final and Analysis Main files:
- Both files can be run on Google collab, or another jupyter kernel, provided that the required packages are downloaded.
- The needed packages and libraries are available in the import section of Analysis Final
- These 2 files import the following classes that have also been submitted alongside both fo these files:
    - a naivebayes class from the naivebayes.py document (the naive bayes we coded from scratch)
    - a textprocessor class from the textprocessor.py document (that processes, and vectorizes  the input data).
    - a custom cross validation class imported from the crossvalidationmp2.py document, that contains our nested k fold cross validation method.