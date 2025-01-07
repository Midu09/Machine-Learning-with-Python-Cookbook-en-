# Machine-Learning-with-Python-Cookbook-en-
Machine Learning with Python Cookbook (en)
Over the last few years machine learning has become embedded in a wide variety of day-to-day business, nonprofit, and government operations. As the popularity of machine learning increased, a cottage industry of high-quality literature that taught applied machine learning to practitioners developed. This literature has been highly successful in training an entire generation of data scientists and machine learning engineers. This literature also approached the topic of machine learning from the perspective of providing a learning resource to teach an individual what machine learning is and how it works. However, while fruitful, this approach left out a different perspective on the topic: the nuts and bolts of doing machine learning day to day. That is the motivation of this book—not as a tome of machine learning knowledge for the student but as a wrench for the professional, to sit with dog-eared pages on desks ready to solve the practical day-to-day problems of a machine learning practitioner.
More specifically, the book takes a task-based approach to machine learning, with almost 200 self-contained solutions (you can copy and paste the code and it’ll run) for the most common tasks a data scientist or machine learning engineer building a model will run into.
The ultimate goal is for the book to be a reference for people building real machine learning systems. For example, imagine a reader has a JSON file containing 1,000 categorical and numerical features with missing data and categorical target vectors with imbalanced classes, and wants an interpretable model. The motivation for this book is to provide recipes to help the reader learn processes such as:
2.5 Loading a JSON file
4.2 Standardizing a Feature
5.3 Encoding Dictionaries of Features
5.4 Imputing Missing Class Values
9.1 Reducing Features Using Principal Components
12.2 Selecting Best Models Using Randomized Search
 
14.4 Training a Random Forest Classifier
14.7 Selecting Random Features in Random Forests The goal is for the reader to be able to:
1.	Copy/paste the code and gain confidence that it actually works with the included toy dataset.
2.	Read the discussion to gain an understanding of the theory behind the technique the code is executing and learn which parameters are important to consider.
3.	Insert/combine/adapt the code from the recipes to construct the actual application.
 
Who This Book Is For
This book is not an introduction to machine learning. If you are not comfortable with the basic concepts of machine learning or have never spent time learning machine learning, do not buy this book. Instead, this book is for the machine learning practitioner who, while comfortable with the theory and concepts of machine learning, would benefit from a quick reference containing code to solve challenges he runs into working on machine learning on an everyday basis.
This book assumes the reader is comfortable with the Python programming language and package management.
 
Who This Book Is Not For
As stated previously, this book is not an introduction to machine learning. This book should not be your first. If you are unfamiliar with concepts like cross- validation, random forest, and gradient descent, you will likely not benefit from this book as much as one of the many high-quality texts specifically designed to introduce you to the topic. I recommend reading one of those books and then coming back to this book to learn working, practical solutions for machine learning.

Terminology Used in This Book
Machine learning draws upon techniques from a wide range of fields, including computer science, statistics, and mathematics. For this reason, there is significant variation in the terminology used in the discussions of machine learning:
Observation
A single unit in our level of observation—for example, a person, a sale, or a record.
Learning algorithms
An algorithm used to learn the best parameters of a model—for example, linear regression, naive Bayes, or decision trees.
Models
An output of a learning algorithm’s training. Learning algorithms train models, which we then use to make predictions.
Parameters
The weights or coefficients of a model learned through training.
Hyperparameters
The settings of a learning algorithm that need to be set before training.
Performance
 
A metric used to evaluate a model.
Loss
A metric to maximize or minimize through training.
Train
Applying a learning algorithm to data using numerical approaches like gradient descent.
Fit
Applying a learning algorithm to data using analytical approaches.
Data
A collection of observations.

Acknowledgments
This book would not have been possible without the kind help of a number of friends and strangers. Listing everyone who lent a hand to this project would be impossible, but I wanted to at least mention: Angela Bassa, Teresa Borcuch, Justin Bozonier, Andre deBruin, Numa Dhamani, Dan Friedman, Joel Grus, Sarah Guido, Bill Kambouroglou, Mat Kelcey, Lizzie Kumar, Hilary Parker, Niti Paudyal, Sebastian Raschka, and Shreya Shankar.
I owe them all a beer or five.


