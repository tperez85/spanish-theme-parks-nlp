# From Stars to Text: Semantic Analysis of Google Maps Reviews in Spanish Theme Parks

## Project Overview
This Master's Thesis investigates the online reputation of the three primary Spanish theme parks: **Parque de Atracciones de Madrid**, **Parque Warner Madrid**, and **PortAventura World**. 

By analyzing a dataset of **74,759 Google Maps reviews**, the project employs advanced Natural Language Processing (NLP) techniques to bridge the gap between numerical star ratings and textual semantic content. The research identifies the core topics, sentiments, and emotions that define the visitor experience, providing a robust framework for Business Intelligence in the leisure and tourism sector.

---

## Repository Structure

The project is organized into two main directories:

### 1. [notebooks/](./notebooks/)
This directory contains the end-to-end data science pipeline, organized into the following sequential notebooks:
* **01_master_dataset_prep .ipynb**: Data acquisition, cleaning, and consolidation of the primary dataset.
* **02_text_preprocessing_nlp.ipynb**: Text normalization, filtering, and NLP-specific preprocessing.
* **03_exploratory_data_analysis.ipynb**: Statistical overview and exploratory data analysis.
* **04_topic_modeling_bertopic.ipynb**: Extraction and labeling of the eight key discussion pillars.
* **05_sentiment_analysis_bert_multilingual.ipynb**: Sentiment classification using a fine-tuned Multilingual BERT model.
* **06_emotion_analysis_zeroshot.ipynb**: Emotion detection using a Zero-shot classification approach with XLM-RoBERTa.
* **07_results_and_visualization.ipynb**: Synthesis of findings, comparative analysis, and Business Intelligence indicators.

### 2. [csv/](./csv/)
Contains the final processed dataset. This file includes the original review data enriched with the following AI-generated features:
* `sentiment_label`: Categorization into Positive, Neutral, or Negative.
* `emotion_label`: Assignment of dominant emotions (e.g., Enthusiasm, Frustration).
* `topic_label`: Thematic classification based on BERTopic results.

---

## Methodology
The analytical framework is built upon state-of-the-art Transformer models:
* **BERTopic**: Utilized for automated and scalable topic discovery.
* **BERT Multilingual**: Fine-tuned to interpret the relationship between text and star ratings.
* **XLM-RoBERTa**: Deployed in a Zero-shot configuration to identify seven distinct emotional categories tailored to the service industry context.

---

## Key Findings
* **The 3-Star Paradox**: Evidence of significant semantic inconsistency in intermediate ratings, where numerical scores often fail to reflect critical operational complaints.
* **Emotional Drivers**: Enthusiasm serves as the primary driver of high satisfaction, whereas Frustration is predominantly linked to wait times, pricing, and service quality.
* **Operational Intelligence**: Deep Learning models demonstrate a superior capacity to transform unstructured feedback into actionable strategic data compared to traditional star-rating metrics.

---

## Author
**Tamara Pérez Pérez** Master in Data Science (Data Science)  
Universitat Oberta de Catalunya (UOC) - 2025
