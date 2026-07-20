📰 Fake News Detection using Machine Learning

📌 Overview

Fake News Detection is a Machine Learning project that classifies news articles as Fake or True based on their textual content. The project applies text preprocessing, feature extraction, and multiple machine learning algorithms to achieve accurate news classification.


🚀 Features

- Detects whether a news article is Fake or True
- Text preprocessing and cleaning
- TF-IDF Vectorization for feature extraction
- Multiple Machine Learning models for comparison
- Manual news prediction using user input
- Model saving using Pickle


🛠️ Technologies Used

Programming Language

- Python

Libraries

- Pandas
- NumPy
- Scikit-learn
- NLTK
- Pickle

Machine Learning Algorithms

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

Feature Extraction

- TF-IDF Vectorizer


📂 Dataset

This project uses two CSV files:

- Fake.csv
- True.csv

The dataset contains news articles labeled as Fake or True for supervised machine learning.


⚙️ Project Workflow

1. Load Dataset
2. Data Cleaning
3. Text Preprocessing
4. TF-IDF Vectorization
5. Train-Test Split
6. Train Multiple ML Models
7. Evaluate Model Accuracy
8. Manual News Prediction
9. Save Trained Model


📊 Model Performance

Model| Accuracy
Logistic Regression| 98.27%
Decision Tree| 99.00%
Random Forest| 97.00%
Gradient Boosting| 99.00%


📁 Project Structure

Fake_News_Detection/
│── dataset/
│   ├── Fake.csv
│   └── True.csv
│── model/
│   ├── logistic_model.pkl
│   └── vectorizer.pkl
│── Fake_News_Detection.ipynb
│── README.md


▶️ Installation

git clone https://github.com/Ankitpal0087/Fake_News_Detection.git

cd Fake_News_Detection

pip install -r requirements.txt


▶️ Run the Project

Open the Jupyter Notebook and run:

jupyter notebook

Then open:

Fake_News_Detection.ipynb

Run all cells in sequence.


📌 Future Improvements

- Flask Web Application
- Streamlit Interface
- Real-Time News Prediction
- Deep Learning Models
- Deployment on Cloud


👨‍💻 Author

Ankit Pal
