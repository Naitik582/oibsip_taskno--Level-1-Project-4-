<h1>Twitter Sentiment Analysis</h1>

**About the Project:**

• This project is about finding the sentiment (positive, negative, or neutral) of text data like tweets, reviews, or comments.
• We used machine learning and NLP (Natural Language Processing) to build a model that understands the emotion behind the text.


**Project Objective:**

• To create a model that can help understand public opinion, customer feedback, and social media trends by analyzing text data.


**Dataset Details:**

• File Name: Twitter_Data.csv

• Columns:

• clean_text: The text content (tweet or comment)

• category: Sentiment label

-1: Negative

0: Neutral

1: Positive


**Steps Followed in the Project:**

1. Data Loading: Loaded the dataset using Pandas


2. Text Cleaning: Removed special characters, stopwords, extra spaces; applied stemming


3. Feature Engineering: Used TF-IDF to convert text into numbers (vectors)


4. Train-Test Split: Divided data into training and testing sets


5. Model Training: Trained the model using Multinomial Naive Bayes algorithm


6. Model Evaluation: Checked accuracy, confusion matrix, and classification report


7. Visualization: Created a bar chart to show how many positive, negative, and neutral texts are there


8. Prediction: Used the model to predict sentiment on new input text




**Libraries Used:**

• Python

• Pandas

• Numpy

• NLTK

• Scikit-learn

• Matplotlib

• Google Colab (Jupyter Notebook)



**How to Run the Project:**

1. Upload the Twitter_Data.csv file to Google Colab


2. Run the code step by step (from data loading to prediction)


3. Try with your own text at the end to test the model



**Final Result:**

• The model successfully predicts the sentiment of any given text

• Accuracy and performance are good for basic real-world testing

• Useful for analyzing opinions on social media or feedback systems
