# Tasks-for-Data-Science-Interns-task-2-

# **Text Sentiment Analysis**

# **Code Explanation:**

 **Import Libraries**
- Used nltk, sklearn, pandas, matplotlib, etc. for text processing, modeling, and evaluation.

 **Load Dataset**

 - IMDB Reviews dataset loaded with pandas directly from a GitHub link.

 **Text Preprocessing**

- Lowercased, removed HTML tags and special characters.

- Removed stopwords and applied lemmatization.

 **Feature Engineering**

- Text converted into numbers using TF-IDF vectorizer (top 5000 words only).

 **Model Training**

- Logistic Regression model trained on the data.

 **Evaluation**

- Accuracy = 88.84%

- Printed classification report & confusion matrix.

 **Prediction Function**

- You can now input any review, and it will return either “Positive” or “Negative”.

# **How to Run the Code:**

**1. Install required libraries:**

!pip install nltk scikit-learn pandas matplotlib seaborn

**2. Download NLTK data:**

nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')

**3. Run each block in order:**

1. Load dataset

2. Preprocess text

3. Split data

4. Vectorize text

5. Train model

6. Evaluate model

7. Use the predict_sentiment() function for predictions

# **Observation:**

1. The model gives 89% accuracy.

2. It predicts sentiment well on real examples.

3. Logistic Regression with TF-IDF works effectively for this task.

4. Preprocessing helped remove noise from text and improved performance.
