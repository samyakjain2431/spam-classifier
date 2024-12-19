# Message Scam Detection  

A robust system for detecting scam messages in real-time using machine learning and natural language processing (NLP) techniques. This project focuses on classifying messages as spam or non-spam to ensure a safer and distraction-free communication environment.

## Features  
- **Real-Time Classification**: Classifies incoming messages dynamically as they are received.  
- **Machine Learning Models**: Implements Naive Bayes and SVM for efficient spam detection.  
- **Text Preprocessing**: Tokenization, stop word removal, and feature extraction using TF-IDF and Word2Vec.  
- **Custom Feature Engineering**: Incorporates features like suspicious word counts and URL detection.  
- **User-Centric Design**: Simple integration with messaging platforms for seamless functionality.  

## Project Workflow  
1. **Data Preparation**  
   - Cleaned and preprocessed message datasets.  
   - Extracted features like keyword frequency and presence of URLs.  
2. **Model Training**  
   - Trained models on labeled datasets using Scikit-learn.  
   - Evaluated performance using precision, recall, F1 score, and accuracy.  
3. **Real-Time Detection**  
   - Integrated trained models for real-time message classification.  
   - Flagged suspicious messages and displayed results instantly.  

## Tools and Libraries  
- **Python**: Primary programming language.  
- **Scikit-learn**: For building and training machine learning models.  
- **NLTK/Spacy**: For text preprocessing tasks.  
- **NumPy & Pandas**: For numerical computations and data manipulation.  
- **Matplotlib/Seaborn**: For visualizing model performance and spam statistics.  
- **Jupyter Notebook**: For development, testing, and debugging.  
