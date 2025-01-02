# **Sentiment Analysis on the Inauguration of the Elected President of Indonesia**

This project focuses on performing sentiment analysis on public opinion regarding the inauguration of the elected president of Indonesia. By leveraging pre-trained transformer models like **BERT** and **IndoBERT**, the project aims to classify sentiments into categories such as positive, negative, and neutral.

---

## **Features**
- **Pre-trained Transformer Models**: Utilizes **BERT** and **IndoBERT** for feature extraction and fine-tuning on Indonesian text.
- **Sentiment Classification**: Categorizes sentiments into positive, negative, and neutral classes.
- **Custom Dataset**: Analyzes real-world social media or news data related to the inauguration.
- **Comprehensive Pipeline**: Includes data preprocessing, model training, evaluation, and visualization.

---

## **Project Workflow**
1. **Data Collection**:
   - Gather text data from sources such as **Twitter**, **news articles**, or other public datasets related to the inauguration.
   - Clean and preprocess the data (e.g., remove duplicates, handle missing values).

2. **Preprocessing**:
   - **Text Tokenization**: Tokenize text using the tokenizer for BERT or IndoBERT.
   - **Text Cleaning**: Remove stopwords, URLs, mentions, and irrelevant content.
   - **Labeling**: Annotate text with sentiment labels (positive, negative, neutral).

3. **Model Training**:
   - Fine-tune **BERT** or **IndoBERT** on the processed dataset.
   - Use a classification head for sentiment classification.

4. **Evaluation**:
   - Evaluate the model on a validation/test set using metrics such as **accuracy**, **precision**, **recall**, and **F1-score**.
   - Compare the performance of BERT and IndoBERT models.

5. **Visualization**:
   - Visualize sentiment distribution, confusion matrices, and prediction examples.

---
