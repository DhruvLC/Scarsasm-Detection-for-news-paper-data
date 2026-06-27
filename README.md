Sarcasm Detection in News Headlines
A Machine Learning and NLP project that detects whether a news headline is sarcastic or non-sarcastic using multiple classification algorithms. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and model serialization.
📌 Project Overview
Sarcasm is difficult for machines to understand because the intended meaning is often opposite to the literal text. This project applies Natural Language Processing (NLP) techniques to classify news headlines as sarcastic or non-sarcastic using traditional machine learning models and a lightweight BERT model.
🚀 Features
Data preprocessing and text cleaning
Exploratory Data Analysis (EDA)
Word frequency and bigram analysis
WordCloud visualization
TF-IDF and Count Vectorization
Multiple machine learning models
Model performance comparison
Model saving using Joblib
📂 Dataset
Dataset: Sarcasm Headlines Dataset v2
The dataset contains:
headline – News headline
is_sarcastic – Target label (0 = Non-Sarcastic, 1 = Sarcastic)
article_link – Original news article URL
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Plotly
NLTK
Scikit-learn
Transformers (BERT Tiny)
PyTorch
Joblib
📊 Workflow
Load Dataset
Clean and preprocess headlines
Perform EDA
Generate WordCloud and Bigram analysis
Tokenize and Lemmatize text
Convert text into numerical features using CountVectorizer and TF-IDF
Train multiple classification models
Evaluate models using Classification Report and ROC-AUC Score
Save trained model and vectorizer
🤖 Models Implemented
Random Forest Classifier
Gaussian Naive Bayes
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
BERT Tiny Transformer
📈 Evaluation Metrics
The models are evaluated using:
Accuracy
Precision
Recall
F1-Score
ROC-AUC Score
📁 Project Structure
Sarcasm-Detection/
│── Scarsasm_Detection_for_news_paper_data.ipynb
│── sarcasm_knn_model.pkl
│── vectorizer.pkl
│── README.md
▶️ Installation
git clone https://github.com/DhruvLC/Scarsasm-Detection-for-news-paper-data.git

cd Sarcasm-Detection

pip install -r requirements.txt
▶️ Run
Open the Jupyter Notebook or Google Colab and execute all cells sequentially.
jupyter notebook
💾 Saved Model
The project exports:
sarcasm_knn_model.pkl
vectorizer.pkl
These files can be used later for inference without retraining the model.
🔮 Future Improvements
Fine-tune larger Transformer models (BERT/RoBERTa)
Deploy using Flask/FastAPI
Build a web interface with Streamlit
Improve accuracy with advanced preprocessing and hyperparameter tuning
👨‍💻 Author
Dhruv Patil
Information Technology Engineer | Data Science & Generative AI Enthusiast
📜 License
This project is intended for educational and learning purposes. Feel free to fork, modify, and build upon it.
