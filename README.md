# USER-BEHAVIOR-IN-OTT-PLATFORM-USING-MACHINE-LEARNING-TECHNIQUES

Evaluated the effectiveness of machine learning algorithms in OTT platforms and determine the most effective algorithms based on their accuracy. ML algorithms can potentially improve content discoverability by precisely anticipating user interests, which can lead to higher levels of user happiness and engagement.

**OBJECTIVES:**
•	To analyze user demographics, viewing habits, content preferences, and engagement patterns of OTT users.
•	To identify a suitable model for the data and analyze it through evaluation metrics and to recommend the optimal machine learning models.
•	To identify user preferences for OTT platforms by identifying the key features that influence their choice.

**METHODOLOGY:**
•	Data Collection and Processing: Primary data was collected (physical questionnaire) from the OTT users about 353 data were collected. 
•	Tools Used: Jupyter Notebook tool used to create and run live code, equations, visualizations, and text. The Python Jypter Lab Version 4.0.9.
•	Exploratory Data Analysis: The data was cleaned and transformed to make it suitable for analysis, modeling, and visualization. The dataset was pre-processed to eliminate errors, missing values, and removing outliers. 
•	Finding the optimal classification: Various Classification models like Random Forest(RF), Decision Tree(DT), Naïve Bayes(NB), Logistic Regression(LR), and Support Vector Machine(SVM) are used to analyze the data. And calculating the evaluation metrics for each model. 
•	Finding the feature importance of the model: The selection model is used to find out the feature importance for the various categories and plot them.

**CLASSIFICATION MODELS:**
	In this study, Classification models like Random Forest (RF), Decision Tree (DT), Naïve Bayes (NB), Logistic Regression (LR), and Support Vector Machine (SVM) are used to analyze the data collected and derive the evaluation metrics can be implemented. The classifier was trained with 80% of the data and tested with the remaining 20%, using 100 trees and a random state of 42. The evaluation metrics used are Accuracy, Precision, Recall, and F-1 Score for the data evaluation. The best-performing model in this study is the Decision Tree (DT) with an Accuracy of 83.09%, and the least ones are Naïve Bayes (NB) and Logistic Regression (LR) with an Accuracy of 33.80% and 36.61%, respectively.
  (Evaluation metrics table)
Methods	   RF	    DT	  NB	 LR	   SVM
Accuracy	76.05	83.09	33.80	36.61	46.47
Precision	74.06	81.14	48.01	34.18	45.59
Recall	  76.05	83.09	33.80	36.61	46.47
F-1 Score	74.93	82.03	28.54	35.00	45.19

   Compares the performance of five machine learning models (RF, DT, NB, LR, and SVM) based on four metrics: accuracy, precision, and recall, F-1 score. The F-1 score, which is the harmonic mean of precision and recall, is also included.
•	From the table, the Decision Tree (DT) model has the highest accuracy of 83.09%, followed by the Random Forest (RF) model with an accuracy of 76.05%. However, the RF model has a higher F-1 score (74.93%) than the DT model (82.03%).
•	Naive Bayes (NB) and Logistic Regression (LR) have the lowest accuracy as it is not suggested for further study. The Naive Bayes (NB) model has the lowest accuracy, precision, recall, and F-1 score among the five models.
•	The Support Vector Machine (SVM) model has a relatively low accuracy (46.47%) but a moderate F-1 score (45.19%). The Logistic Regression (LR) model has a similar accuracy (36.61%) and F-1 score (35.00%) less than the SVM model.

**Decision Tree:**
   Classification model performance: The decision tree (DT) model achieved the highest accuracy (83.09%) for predicting user platform choice among the models tested: Random Forest (RF), Support Vector Machine (SVM), Logistic Regression (LR), and Naive Bayes (NB). Naive Bayes and Logistic Regression had the lowest accuracy (33.80% and 36.61%, respectively).
Feature importance: Analysis of the decision tree revealed the following features to have the most significant influence on user platform selection 
(feature importance > 0.05):
•	Download content for offline view – 0.1132
•	Binge-watch content – 0.0867
•	Feeling personalized on the content watching – 0.0831
•	Cancel subscription price increases: 0.0706
•	Social features like sharing, rating the content, and recommendations – 0.0611
•	Video quality offered: 0.0660
•	Share content with others: 0.0636
•	Search function: 0.0629
These features would help the OTT platform to increase the viewership of their content and attract their customer to their platform. It helps to improve user experience and platform adoption. 

**Random Forest:**
	Random forest features are extracted as it has a decent score of accuracy with 76% So, the feature importance is used to compare the top feature of the random forest. 
Feature importance: Analysis of the Random Forest revealed the following features to have the most significant influence on user platform selection 
(feature importance > 0.05):
•	Original content viewing – 0.0694
•	Binge-watch content – 0.0668
•	Buffering or lag on the content– 0.0663
•	Rewatch content – 0.0656
•	Download content for offline view – 0.0651
•	Cancel your subscription price increases – 0.0650
•	Feeling personalized on the content watching – 0.0639
•	Search function – 0.0630
•	Video quality offered by the platform – 0.0622
These features are recommended by the random forest as features important to increase the viewership of the OTT platforms if they use this model.

**FINDINGS:**
	The objective of this study has been accomplished as it represents the classification model of the dataset and the further importance of the features has been found out in this process. The major findings are:
•	Classification models such as Random Forest (RF), Decision Tree (DT), Naïve Bayes (NB), Logistic Regression (LR), and Support Vector Machine (SVM) are used to identify model performance using evaluation metrics. Accuracy determines the model performance where the acquired values are Random Forest (RF) at 76%, Decision Tree (DT) at 83%, Naïve Bayes (NB) at 34%, Logistic Regression (LR) at 37%, and Support Vector Machine (SVM) with 46%.
•	From the dataset it is found that Decision Tree has 83% accuracy in the classification model. It is analyzed by the variable OTT mostly viewed by the users.
•	The data also helps to derive the relevant feature importance to the Decision Tree model. Download content for offline viewing, Buffering or lag on the content, Binge-watch content, Feeling personalized on the content watching, Continuing subscribing to the same platform, Original content viewing is an important feature to be focused on for user satisfaction and platform loyalty.
•	The decision tree model appears to be the most effective model for predicting user platform choice based on the features analyzed. This also reveals important user behavior patterns that OTT platforms can leverage to improve user experience and increase content viewership.
•	The most important feature of the Decision Tree model is Download content for offline view – 0.1372. The most important feature of the Random Forest model is Original content viewing – 0.0694
•	This feature importance analysis provides insight into the features that have the most influence in determining the user's choice of OTT platform. This understanding can be used to inform future decision-making and improve the user experience.

**SUGGESTIONS:**
•	The analysis highlights the importance of original content. Invest in creating high-quality content that cater to different user preferences.
•	Download for offline viewing is a feature that is a top priority for users. Ensure a seamless experience for downloading content for offline viewing.
•	Price sensitivity is a major factor for users (reflected by "Cancel subscription if  price increases") for offering competitive pricing.

**CONCLUSION:**
	 This research focuses on the EDA of the data and explores techniques for classification problems and their application in selecting an efficient OTT platform. Methods, including classification, and evaluation metrics to analyze the data. The Decision Tree (DT)model, known for its effectiveness in other domains like demographics and features, is implemented for OTT platform selection as the decision tree has an accuracy of 83% in this research. Accuracy improves data more relevant feature selection enhances system performance, and reliable and relevant data is crucial for optimal results. The findings assist individuals and organizations in making informed choices, highlighting the importance of evaluating features and parameters. 
   This research found that the target audience of the age group 15-24 and 25-34 are mostly using the OTT platform and prefer to watch movies and web series content the most they are mostly influenced by social media to watch content. Not only the particular genre all genres are mostly preferred by the users.  Using feature importance, it found that the Download content for offline viewing, Buffering or lag on the content, and Binge-watch content should be focused on to acquire more users in the particular platform. This research lays the groundwork for further exploration of machine learning in the OTT industry, offering valuable perspectives for complex problem-solving. Feature importance helps to analyze the particular areas that would enhance the business growth of the OTT platform.

