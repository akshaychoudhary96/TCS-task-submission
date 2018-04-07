# TCS-task-submission

Prerequisites
•	Download the pre-trained word vectors, namely glove.840B.300d, from https://nlp.stanford.edu/projects/glove/ and put it into the project directory.
•	Download the train and test data from https://www.kaggle.com/c/quora-question-pairs/data. Create a folder named "data" and put them in.
•	Install all the packages in requirements.txt.

Pipeline
•	First run nlp_feature_extraction.py and non_nlp_feature extraction.py scripts. They may take an hour to finish.
•	Then run model.py which may take around 5 hours to make 10 different predictions on the test set.
•	Finally, ensemble and postprocess the predictions by postprocess.py
