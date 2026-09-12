# Review Data Analysis & Authenticity Detection | ML, TF/IDF, Sk Learn, Pandas, Python

**Research Paper Published:** https://propulsiontechjournal.com/index.php/journal/article/view/11043

In recent years, the World Wide Web has drastically changed the way of sharing opinions. Online reviews are comments, tweets, posts, opinions on different online platforms. Customer analyzes available reviews and makes a decision whether to purchase the product or not. Fake or spam review refers to any unsolicited and irrelevant information about the product or service. Spammer writes fake reviews about the competitors’ products and promotes their own products.

In order to remove this type of fake reviews and provide the users with the original reviews and rating related to the products, we proposed a Fake Product Review Monitoring and Removal System (FaRMS) which is an Intelligent Interface and takes the Uniform Resource Locator (URL) related to products of Amazon, Flipkart, Yelp and Daraz and analyzes the reviews, and provides the customer with the original rating.

## Objectives:
Develop a multi-model ML system for classifying online reviews.
Compare and evaluate models to improve accuracy.
Integrate with e-commerce site and show visual results.
Identify suspicious reviews and help users make informed decisions.

## Methodology:
1. Data Collection: Labeled datasets of real vs. fake reviews
2. Preprocessing: Tokenization, stopword removal, punctuation cleaning
3. Feature Extraction: TF-IDF vectorization
4. Model Training: Ensemble (Logistic Regression, Naive Bayes, Decision Tree)
5. Evaluation: Accuracy, precision, recall
6. Real-Time Integration: Live prediction and Integration with Ecommerce website


![image](https://github.com/user-attachments/assets/2978fee8-c487-4eec-85d0-539da1d525d2)

## Dataset:
Data Context: The dataset was sourced from Kaggle, originally scraped from Booking.com, and is publicly available. It contains 11,912 hotel reviews, including both positive and negative reviews, with real/fake labels. 


## Requirements: Use pip install/conda install to download following packages
Numpy, pandas
sklearn
spacy
Django 2.1
pickle
tqdm

## running the app:
Go to folder containing manage.py and run command: python manage.py runserver
Once the server starts, open browser. The app runs on http://127.0.0.1:8000/
fake_reviews.txt and real_reviews.txt contains some reviews that can be used to test the working of model.


 The target of this task is to foster a mechanized framework fit for recognizing
 counterfeit surveys from a lodging surveys dataset. The framework will use a few AI
 (ML) calculations, including Choice Tree, K-Closest Neighbors (KNN), Strategic
 Relapse, and Backing Vector Machines (SVM), to characterize surveys as either
 certifiable or counterfeit. 

## Conculsion:
The model demonstrated effective performance in detecting fake reviews using the existing dataset.
SVM with RBF kernel achieved the highest accuracy of 88% among the models evaluated.
The results indicate that the proposed approach can be used as a machine-learning-based solution for fake review detection.



