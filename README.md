# plagiarism-detectior

The task of this project was to create a plagiarism detector with custom similarity features between source and answer files and longest common subsequence. I trained and deployed a decision tree model on Amazon Sagemaker.

The feature engineering follows the presented methods of this [paper](https://s3.amazonaws.com/video.udacity-data.com/topher/2019/January/5c412841_developing-a-corpus-of-plagiarised-short-answers/developing-a-corpus-of-plagiarised-short-answers.pdf) and is presented in this [notebook](https://github.com/felix-ha/plagiarism-detectior/blob/master/2_Plagiarism_Feature_Engineering.ipynb). The trainig, evaluating and deployment on AWS of the model is presented in this [notebook](https://github.com/felix-ha/plagiarism-detectior/blob/master/3_Training_a_Model.ipynb). 

This project was part of the Udacity Machine Learning Engineer Nanodegree.