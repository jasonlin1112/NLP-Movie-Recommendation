# 🎬 IMDb Movie Review Sentiment Analysis

•	This project uses **NLP** and **Machine Learning** to analyze IMDb movie reviews and classify them as either positive or negative. 

•	Built with **Python** and **Streamlit**, it leverages real-time data, advanced preprocessing, and interpretable models to deliver robust sentiment insights for movie audiences.

## **📌 Project Goals**

•	Automate sentiment classification of movie reviews

•	Deliver real-time sentiment analysis through an interactive interface

•	Evaluate model performance through robust metrics and validation

•	Enable decision-makers to derive actionable insights from review data


## **🧠 Workflow Overview**

  ### **1. 	📥 Data Collection**
  
•	Dataset: IMDb 50K Movie Reviews

•	API: Live review retrieval via OMDb API

•	Why OMDb? Circumvents scraping issues, provides structured movie data



### **2. 🧹 Data Preprocessing**

Performed standard NLP cleaning steps:


•	Remove missing values


•	Convert text to lowercase


•	Remove HTML tags & special characters


•	Tokenization


•	Stopword removal


•	Label standardization


### **3. 🤖 Model Training**

We trained and compared:

<img width="678" alt="Screenshot 2025-04-20 at 2 10 04 AM" src="https://github.com/user-attachments/assets/d896344f-b72b-4352-9d9a-6aa8d375a10a" />


**•	Logistic Regression: 88.78% Accuracy**

•	Support Vector Machine: 88.28% Accuracy

•	Random Forest: 83.49% Accuracy

###  **4. ⚙️ Feature Engineering**

<img width="734" alt="Screenshot 2025-04-20 at 2 12 11 AM" src="https://github.com/user-attachments/assets/11ab7f3b-c077-4e83-915e-d2d22ea3a6df" />

**•	TF-IDF + Logistics Regression: 88.78% Accuracy**

•	Word Embeddings + Logistics Regression: 75.73% Accuracy

#### 🔑 Key Finding: TF-IDF + Logistic Regression was the most effective combination.



### **5. 📊 Model Evaluation**

#### **Assessing Performance with Confusion Matrix, Precision/Recall, and ROC-AUC**
![Screenshot 2025-04-20 at 2 32 16 AM](https://github.com/user-attachments/assets/b888fce0-27a6-4767-8439-fb05d8246663)
![Screenshot 2025-04-20 at 2 32 36 AM](https://github.com/user-attachments/assets/de8ce689-d2c9-4c3f-94b6-4bfd6d48a662)


### **Metrics:**
![Screenshot 2025-04-20 at 2 28 11 AM](https://github.com/user-attachments/assets/9aa6cccc-0667-4c20-9128-d0f5cca9ae76)

•	Precision: 0.90 (Neg), 0.88 (Pos)

•	Recall: 0.88 (Neg), 0.90 (Pos)

•	F1-Score: 0.89 (both)

•	Overall Accuracy: 89%

•	AUC Score: 0.96

### 6. ✅ Validation with LLM Ground Truth

#### **Compared predictions with a Large Language Model:**
![Screenshot 2025-04-20 at 2 29 28 AM](https://github.com/user-attachments/assets/d5901ba3-d03f-436e-a4f0-8974445c0d0d)
![Screenshot 2025-04-20 at 2 29 47 AM](https://github.com/user-attachments/assets/c39a0e13-c02d-4845-b885-3bd6d63d8d24)

•	Accuracy: 83.3%

•	AUC Score: 0.79

**•	Showed slightly better performance in identifying positive sentiments**

### 7. 🖥️ Interactive User Interface

**Built with Streamlit:**

•	Accepts movie name input

•	Fetches reviews via OMDb API

•	Analyzes sentiment in real-time

•	Displays results with visual breakdown (bar chart)

#### **Try the Demo: https://imdb-sentiment-analysis-movie-reviews.streamlit.app/**

![Screenshot 2025-04-20 at 2 37 37 AM](https://github.com/user-attachments/assets/d14f7f77-3b56-433f-9e3e-8a5b43b94651) ![Screenshot 2025-04-20 at 2 38 01 AM](https://github.com/user-attachments/assets/1f9a1b51-ad1b-48ed-875c-d54603a1cd56)

### **🔍 Future Enhancements**

•	Add topic modeling (e.g., LDA) to extract themes

•	Integrate additional review sources (e.g., Rotten Tomatoes)

•	Improve UI/UX design and visual analytics

•	Deploy as a web app for public use


