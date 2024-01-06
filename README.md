# SMS-Spam-Classifier

This project focuses on classifying spam SMS messages using machine learning techniques. The dataset was sourced from Kaggle, providing a diverse set of text messages for training and evaluation. The project follows a structured workflow to achieve an effective spam classification model. Let's delve into the key steps involved:

# 1. Data Cleaning
The initial step involves cleaning the dataset by removing unnecessary columns and handling null values. This ensures a clean and reliable dataset for subsequent analysis.

# 2. Exploratory Data Analysis (EDA)
EDA aims to uncover patterns and relationships within the dataset. In this project, we explore the relationships between words, statements, and their correlation to spam or non-spam messages.

# 3. Text Preprocessing
To prepare the text data for model training, several preprocessing steps are performed:

Converting text to lowercase
Tokenization
Removing special characters
Removing stop words and punctuation
Stemming

# 4. Model Building
The classification model is built using the TF-IDF vectorizer with a maximum of 3000 features and a Multinomial Naive Bayes classifier. This combination has proven effective in capturing the essence of the text messages.

# 5. Evaluation
After model training, evaluation metrics such as accuracy, precision, recall, and F1 score are employed to assess the model's performance in distinguishing between spam and non-spam messages.

# 6. Improvement
The project includes a phase dedicated to exploring potential improvements. This involves tweaking parameters, experimenting with different models, and refining the preprocessing steps to enhance the classifier's accuracy.

# 7. Web Application
The project goes beyond model building and introduces a user-friendly web application using Streamlit. This allows users to interact with the spam classifier in a seamless and intuitive manner.

# 8. Deployment
Deployment is a crucial aspect of making the classifier accessible to the public. By leveraging Streamlit and GitHub, the project is deployed, allowing users to classify SMS messages for spam directly from the web.

To facilitate the deployment process, requirements.txt lists essential dependencies, and nltk.txt is utilized to download additional resources like stopwords and punkt for text processing.

This Spam SMS Classifier project showcases the end-to-end process of building, refining, and deploying a machine learning model for practical use, making it a valuable tool for identifying spam messages in SMS communications.
