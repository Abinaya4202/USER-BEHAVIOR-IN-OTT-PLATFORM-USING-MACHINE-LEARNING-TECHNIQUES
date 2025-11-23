# USER-BEHAVIOR-IN-OTT-PLATFORM-USING-MACHINE-LEARNING-TECHNIQUES

The effectiveness of machine learning algorithms in OTT platforms and determine the most effective algorithms based on their evaluation metrics. ML algorithms can potentially improve content discoverability by precisely anticipating user interests, which can lead to higher levels of user happiness and engagement.


**OBJECTIVES:**


•	To analyze user demographics, viewing habits, content preferences, and engagement patterns of OTT users.
•	To identify a suitable model for the data and analyze it through evaluation metrics by applying ML models to predict high user satisfaction.
•	Suggest improvement for OTT services by identifying the key features that influence their choice.


**METHODOLOGY:**


•	Data Collection and Processing: Primary data was collected (physical questionnaire) from the OTT users about 353 data were collected. 
•	Tools Used: Jupyter Notebook tool used to create and run live code, equations, visualizations, and text. The Python Jypter Lab Version 4.0.9.
•	Exploratory Data Analysis: The data was cleaned and transformed to make it suitable for analysis, modeling, and visualization. The dataset was pre-processed to eliminate errors, missing values, and removing outliers. 
•	Finding the optimal classification: Various Classification models like Random Forest(RF), Decision Tree(DT), Naïve Bayes(NB), Logistic Regression(LR), and Support Vector Machine(SVM) are used to analyze the data. And calculating the evaluation metrics for each model. 
•	Finding the feature importance of the model: The selection model is used to find out the feature importance for the various categories and plot them.


**DESCRIPTIVE ANALYSIS:**


•	The analysis examined OTT users demographic characteristics, usage patterns, content preferences, satisfaction factors, and the key determinants influencing overall user experience. 
•	Descriptive statistics showed that most respondents were aged 18–24, with students forming the majority demographic. 
•	Netflix, Amazon Prime, and Disney+ Hotstar emerged as the most commonly used OTT platforms. A large portion uses 2–3 platforms concurrently.This indicates multi-platform consumption behavior typical in India.
•	Usage frequency was high, with many users accessing OTT services daily and spending 1–3 hours per day on average.


**Likert Satisfaction Factor Summary**


•	Highest-rated of mean score falls on Video quality offered, Original content, Recommendations, Content variety, Search function usability
•	Lowest-rate of mean score falls on Social features, Rewatch content, Share content with others, Offline viewing


**CLASSIFICATION MODELS:**


•	Machine learning models like Logistic Regression, Decision Tree, Random Forest, Naive Bayes, and SVM were used to predict whether users reported high overall experience. 
•	Among these, the Random Forest classifier achieved the strongest accuracy and F1-score, making it the most reliable model. 
•	Feature importance analysis from Random Forest showed that factors such as sharing accounts, original content, and video quality offered contributed the most to predicting high user satisfaction, whereas features like offline downloads and social features had comparatively lower influence.
•	The analysis indicates that user satisfaction is multidimensional and strongly tied to content quality, technical performance, personalization, and flexible platform features.


**FINDINGS:**


1. Video quality, personalization, and content variety are the top-rated satisfaction factors. Users prioritize smooth streaming, high resolution, and diversified content libraries when evaluating OTT platforms.

2. Account-sharing features are highly influential. The Random Forest model identified “Share accounts with others” as the highest contributor to predicting satisfaction, suggesting that users value flexible multi-user accessibility.

3. Original content has a major impact on satisfaction. Exclusive shows and movies significantly shape the user’s overall experience and platform loyalty.

4. User engagement features matter moderately. Recommendations and search functions show moderate importance, indicating that content discoverability influences the viewing experience.

5. Random Forest is the best-performing predictive model. It achieved the highest accuracy (~90%) and F1 score, outperforming Logistic Regression, Decision Tree, Naive Bayes, and SVM.

6. Users prefer convenience and ease of access. Smartphones are the most used devices, followed by smart TVs, confirming a preference for portable, easy-to-access streaming.


**CONCLUSION:**


The study successfully analyzed OTT user behavior, preferences, and satisfaction using survey responses and machine learning techniques. The findings indicate that video quality, original content, personalization, and account-sharing flexibility are the most influential factors determining overall satisfaction. These elements distinguish OTT platforms in a highly competitive market and play a crucial role in retaining users.

Machine learning models further validated these insights, with the Random Forest classifier emerging as the most reliable model for predicting user satisfaction. Its feature importance analysis highlighted the key drivers of satisfaction, providing actionable insights for OTT service providers.

Overall, the project demonstrates that OTT platforms can significantly improve user satisfaction and retention by focusing on enhanced streaming quality, rich original content, personalized recommendations, and flexible subscription features. These findings not only support academic understanding but also offer practical implications for OTT industry strategies and customer experience improvements.


**SUGESSION**


The results of this study highlight the need for OTT platforms to strengthen core service areas such as original content, video quality, and personalized recommendations, as these factors were found to be the most influential in determining user satisfaction. Investing in high-quality exclusive content, reducing buffering issues, and improving adaptive streaming technology can greatly enhance the overall viewing experience. Additionally, platforms should focus on refining their recommendation algorithms and improving search functionality to make content discovery easier and more relevant for users. Since a majority of respondents use smartphones for streaming, optimizing the mobile app interface, performance, and data consumption will further support a seamless and enjoyable user experience.

The feature importance results also revealed that account-sharing flexibility plays a major role in shaping user satisfaction. Therefore, OTT platforms should consider introducing more affordable and flexible subscription plans, including family packs, student discounts, and multi-device access options. Although features such as offline downloads and social interactions showed lower importance, retaining these features can still add value for specific user groups without requiring significant development effort. Finally, expanding regional content offerings and strengthening personalization could help platforms reach broader audiences and improve customer retention. By focusing on these high-impact areas, OTT providers can enhance user satisfaction and remain competitive in an evolving digital entertainment landscape.


**FUTURE SCOPE**


This project can be expanded in the future by collecting a larger and more diverse dataset to improve the accuracy and generalizability of the results. More advanced machine learning techniques such as XGBoost, Gradient Boosting, and Neural Networks can be applied to achieve deeper insights into user satisfaction. 
Additional behavioral data like viewing duration, watch history, and user engagement metrics can be integrated to understand real-time patterns beyond survey responses. Sentiment analysis of user reviews and social media discussions can further enhance the understanding of user expectations. 
The project can also evolve into a full-fledged recommendation system or an interactive analytics dashboard that OTT companies can use to monitor user satisfaction, identify areas of improvement, and make data-driven decisions for customer retention and personalized content delivery.
