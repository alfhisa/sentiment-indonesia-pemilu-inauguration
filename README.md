# **Sentiment Analysis on the Inauguration of the Elected President of Indonesia**

This project focuses on analyzing public sentiment on Twitter regarding the inauguration of the elected president and vice president of Indonesia. By leveraging multiple pre-trained transformer-based models, the project compares sentiment predictions and trends while providing in-depth insights through visualization and analysis.

---

## **Features**
- **Data Crawling**: Collects tweets discussing the inauguration using Twitter's API.
- **Transformer Models**: Utilizes multiple pre-trained sentiment analysis models fine-tuned on Indonesian text:
  - [mdhugol/indonesia-bert-sentiment-classification](https://huggingface.co/mdhugol/indonesia-bert-sentiment-classification)
  - [w11wo/indonesian-roberta-base-sentiment-classifier](https://huggingface.co/w11wo/indonesian-roberta-base-sentiment-classifier)
  - [StevenRiyaldi/Indonesia-Pemilu-Sentiment-Classification](https://huggingface.co/StevenRiyaldi/Indonesia-Pemilu-Sentiment-Classification)
- **Comprehensive Analysis**:
  - Sentiment distribution comparison across models.
  - Sentiment trends over time.
  - Agreement and confusion matrices between models.
  - Sentiment analysis on key terms and topics.
  - Word cloud visualization based on sentiment.

---

## **Project Workflow**
1. **Data Collection**:
   - Crawl tweets related to the inauguration using Twitter's API.
   - Filter tweets based on relevance (keywords like "pelantikan presiden," "wakil presiden terpilih," etc.).

2. **Preprocessing**:
   - Remove irrelevant content (URLs, mentions, hashtags, duplicates).
   - Normalize text for consistency.

3. **Sentiment Analysis**:
   - Use the following pre-trained transformer-based models for sentiment classification:
     - **mdhugol/indonesia-bert-sentiment-classification**
     - **w11wo/indonesian-roberta-base-sentiment-classifier**
     - **StevenRiyaldi/Indonesia-Pemilu-Sentiment-Classification**
   - Predict sentiment for each tweet (positive, negative, neutral).

4. **Analysis and Visualization**:
   - **Sentiment Distribution Comparison**: Compare the distribution of sentiments predicted by each model.
   - **Sentiment Trend Over Time**: Visualize how sentiment evolves during the inauguration period.
   - **Agreement Between Models**: Analyze the level of agreement between different models.
   - **Sentiment Confusion Matrix**: Highlight discrepancies in sentiment predictions.
   - **Sentiment Analysis on Key Terms/Topics**: Identify dominant sentiments around specific terms/topics (e.g., "presiden," "pelantikan").
   - **Word Cloud**: Generate word clouds based on positive, negative, and neutral sentiments.

---
