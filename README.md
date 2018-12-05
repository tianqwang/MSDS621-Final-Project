# Toxic Comment Classification
### Group Project for MSDS621 Machine Learning at University of San Francisco

### Group Member
Shivee Singh  
Neha Tevathia  
Mengting (Joyce) Chang  
Xinran(Grace) Zhang  
Tianqi Wang  

### Table of Content
- Dataset Overview
- Data Preprocessing and EDA
- Model Fitting and Results

### Dataset Overview
The threat of abuse and harassment online prevent many people from expressing themselves and make them give up on seeking different opinions. In the meantime, platforms struggle to effectively facilitate conversations, leading many communities to limit or completely shut down user comments. Therefore, Kaggle started this competition with the Conversation AI team, a research initiative founded by Jigsaw and Google. The competition could be found here: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge

As a group of students with great interests in Natural Language Processing, as well as making online discussion more productive and respectful, we determined to work on this project and aim to build a model that is capable of detecting different types of toxicity like threats, obsenity, insults, and identity-based hate. 

The dataset we are using consists of comments from Wikipedia’s talk page edits. These comments have been labeled by human raters for toxic behavior. The types of toxicity are:
- toxic
- severe_toxic
- obscene
- threat
- insult
- identity_hate

There are 159,571 observations in the training dataset and 153,164 observations in the testing dataset. Since the data was originally used for a Kaggle competition, in the test_labels dataset there are observations with labels of value -1 indicating it was not used for scoring.

### Data Preprocessing and EDA

![alt text](https://user-images.githubusercontent.com/40482785/49547102-af9ec180-f896-11e8-9213-df5ef098f8c6.png)

![alt text](https://user-images.githubusercontent.com/40482785/49547039-90079900-f896-11e8-8e99-f83e327757ac.png)



### Model Fitting and Results


