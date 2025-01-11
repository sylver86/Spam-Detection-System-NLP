# 📧 NLP Spam Detection System

### 👋 Overview
This project aims to build a robust **NLP tool** that:
1. Classifies emails as **SPAM** or **NOT SPAM**  
2. Identifies key **topics** in spam emails and measures their **semantic distance**  
3. Extracts **organizations** mentioned in non-spam emails  

Leveraging libraries such as **spaCy** and **NLTK**, this system provides **end-to-end** solutions for text classification, topic modeling, semantic similarity, and named entity extraction.

---

## 🎯 Project Objectives

1. **Train a Classifier for SPAM Identification**  
   - Use the provided dataset to train a machine learning model that accurately labels emails as SPAM or NOT SPAM.  
   - Evaluate performance with metrics like **accuracy**, **precision**, **recall**, and **F1-score**.

2. **Identify Main Topics in SPAM Emails**  
   - Perform **topic modeling** (e.g., **Latent Dirichlet Allocation (LDA)**) to uncover key themes in spam messages.

3. **Calculate the Semantic Distance Between Topics**  
   - Measure how distinct each topic is using metrics like **cosine similarity**.  
   - Assess diversity and overlap of the discovered themes.

4. **Extract Organizations from NON-SPAM Emails**  
   - Apply **Named Entity Recognition (NER)** (using **spaCy** or **NLTK**) to detect and extract organization names in non-spam emails.

---

## 🏗️ Project Structure

1. **Data Preprocessing**  
   - Clean and prepare the dataset for model training (e.g., removing noise, normalizing text).  
   - Implement **tokenization**, **stop-word removal**, **lemmatization**, and **stemming**.

2. **Classifier Training**  
   - Experiment with various algorithms (e.g., **Naive Bayes**, **SVM**, or neural networks).  
   - Select and fine-tune the best model based on validation metrics.

3. **Topic Modeling (SPAM Emails)**  
   - Use **LDA** to identify dominant topics in spam emails.  
   - Visualize and interpret the most common themes.

4. **Semantic Distance Computation**  
   - Implement methods (like **cosine similarity**) to measure how similar or different identified topics are.

5. **Named Entity Recognition (NER)**  
   - Use **spaCy** or **NLTK** to detect and extract organization names from non-spam emails.

---

## 🔧 Libraries & Tools

- **spaCy**: Named Entity Recognition, tokenization, lemmatization  
- **NLTK**: Tokenization, stop-word removal, text preprocessing  

---

View my code on ipynb files! Happy coding! ✨
