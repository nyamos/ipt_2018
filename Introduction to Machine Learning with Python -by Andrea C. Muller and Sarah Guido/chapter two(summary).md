# Supervised Learning
supervised learning machine learning is commonly used machine learning for predicting certain outcome from a given input. The model is built using a input/output pairs which containing our training data.
The two major types of supervised machine learning **_classification_** and  **_regression_**. 

Classfication tasks predict class label given an input. classification is divided into _binary calssification_,which involve classfying between twoo
 classess its a typical yes or no prediction, example of binary classification; samp filter (predict if an email is spam or not spam) and another is _multiclass classification_ it involve more than two classes, example will be like predict what language a website is in from the text on the website, the classess here will be list of languages.
 
 Regression tasks is predicting a _continuous number or floating point value_. for example predicting person's annual income from their education, age, where they live, the predicted income is an amount or numerical value which can be a number in a given range.
 
 ## Generalisation, Overfitting, Underfitting
 when the model is able to accurately predict on unseen data, we say it is able to generalise from training set to the test set. 
 when the model is too complex compare to the data to be operated on, this is calles **_overfitting_**. Overfitting occur when you fit your model to closely on the features of training set, hence makes model perform well on train but poor on predict new data.  
 **_Underfitting_** occur when the model is simple compare to reality of the data we have. underfitting miss to consider some features and variability in the data which can result in poor performance even in the training phase of the model.  
 
 Therefore, our model should not be too simple or too complex, just complex enough to have a better generalization on a new data, because the more complex is the model the more you get better generalisation, but careful not make the model too complex, so it start focusing an indivudual in our data which will lead to bad generalisation on new data.  
 To clarify things so that we are clear on overfitting, we have the right model a too complex one, its just that the datset is not a large variety one to balance with indivuals which our too complex model is focusing on. So having a more complex model for better generalisation, its begs for larger variety of dataset to avoid overfitting. 
 
 




