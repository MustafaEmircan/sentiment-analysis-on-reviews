# Sentiment Analysis for Amazon Reviews 🛍️📝

## BUSINESS PROBLEM  
Kozmos, a company focused on producing home textiles and casual wear, is looking to improve its products by analyzing customer feedback. By understanding the sentiment behind the reviews, 
Kozmos can address complaints and enhance product features. This project focuses on performing sentiment analysis on customer reviews, with the aim of tagging the data for sentiment classification.

## TO DO:
- Preprocess the dataset for sentiment analysis 🔄
- Perform sentiment analysis and statistical evaluation 📊
- Build and evaluate classification models based on tagged data 🤖

## FEATURES
- **Star**: Number of stars given to the product ⭐  
- **HelpFul**: Number of people who found the review helpful 👍  
- **Title**: Title or short comment of the review 📝  
- **Review**: Detailed review of the product 💬  

## DATASET STORY  
The dataset is made up of reviews related to a specific product group. It includes the review title, star rating, how many users found the review helpful, and the full review text.

## ANALYSES MADE:
- **Text Preprocessing**: Cleaned and tokenized review text by removing special characters, stop words, and converting text to lowercase 🧹📝  
- **Sentiment Labeling**: Labeled the sentiment of the reviews as positive, neutral, or negative based on the text content 🏷️  
- **Vectorization**: Used TF-IDF (Term Frequency-Inverse Document Frequency) to transform text data into numerical format for model input 🔢  
- **Model Evaluation**: Evaluated model performance using accuracy, confusion matrix, precision, recall, and F1-score 📉✅  
- **Cross-Validation**: Used k-fold cross-validation to ensure model robustness and prevent overfitting 🔍🎯  

## MACHINE LEARNING MODELS USED:
- Logistic Regression  
- RandomForestClassifier  

## ABOUT THE DATA  
This dataset consists of Amazon customer reviews, focusing on specific product groups. Each entry contains detailed feedback, a star rating, and whether the review was marked as helpful by other users. 
The goal of this project is to classify the sentiment of each review, helping Kozmos understand customer satisfaction and improve product quality accordingly.

# 📬 Contact
If you have any questions or feedback, feel free to reach out via GitHub issues or email. Your insights are valuable! 😊
