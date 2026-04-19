# Hyperlocal-News-Anomaly-Detection-Source-Attribution🚀 Project Overview
This project builds an advanced NLP-powered system to detect anomalous patterns in hyperlocal news articles and identify source misattribution. It analyzes linguistic signals, sentiment, topics, and geographic cues to flag misleading or unusual news content.
The system combines transformer-based embeddings, unsupervised anomaly detection, and geospatial NLP to ensure reliable and interpretable insights.

# Objectives


Detect linguistic anomalies in news articles


Identify source-location discrepancies


Monitor temporal shifts in topics & sentiment


Provide interpretable anomaly scores


Visualize insights via an interactive dashboard



#  Key Features


 Location Extraction (NER) from unstructured text


 Sentiment Analysis using transformer models


 Topic Modeling (BERTopic / LDA)


 Anomaly Detection


Isolation Forest


One-Class SVM


Deep Autoencoders




 Source Attribution Model


 Temporal Trend Analysis


 Interactive Dashboard (Streamlit/Dash)



# Tech Stack
Languages & Libraries


Python


scikit-learn


PyTorch / TensorFlow


Pandas, NumPy


NLP & ML


Transformers (BERT, RoBERTa)


SpaCy / Stanza (NER)


BERTopic / LDA


VADER / Transformer-based Sentiment


Visualization


Streamlit / Dash


Matplotlib / Plotly


Cloud


AWS / GCP (Deployment)


# Project Structure
hyperlocal-news-anomaly/│── data/│   ├── raw/│   ├── processed/││── notebooks/│   ├── EDA.ipynb│   ├── preprocessing.ipynb│   ├── modeling.ipynb││── src/│   ├── preprocessing.py│   ├── ner_location_extraction.py│   ├── sentiment_analysis.py│   ├── topic_modeling.py│   ├── feature_engineering.py│   ├── anomaly_detection.py│   ├── source_attribution.py│   ├── temporal_analysis.py││── models/│   ├── saved_models/││── app/│   ├── streamlit_app.py││── requirements.txt│── README.md│── LICENSE

# Workflow


Data Preprocessing


Cleaning, tokenization, lemmatization


Date feature extraction




Feature Engineering


Transformer embeddings


Sentiment scores


Topic distributions


Location features




Modeling


Unsupervised anomaly detection


Source attribution classifier




Evaluation


AUC-ROC, Precision, Recall, F1-score


Recall@K




Visualization


Dashboard for anomaly insights





# Results


 Detected linguistic & temporal anomalies


 Identified source misattribution cases


 Generated interpretable anomaly scores


 Visualized geo-temporal trends



# Evaluation Metrics


AUC-ROC / PR Curve


Precision, Recall, F1-score


Recall@K


Source Attribution Accuracy



# Deployment


Hosted on AWS / GCP Cloud


Interactive dashboard accessible via web



# Installation
git clone https://github.com/your-username/hyperlocal-news-anomaly.gitcd hyperlocal-news-anomalypip install -r requirements.txt

# Run Application
streamlit run app/streamlit_app.py

# Use Cases


 Disinformation Detection


 Brand Reputation Monitoring


 Hyperlocal Trend Analysis


 Automated News Verification



# Challenges


Accurate location extraction from text


Handling ambiguous geographic entities


Lack of labeled anomaly data


Ensuring model interpretability



# Future Improvements


Real-time news streaming integration


Multilingual support


Graph-based anomaly detection


Explainable AI (XAI) integration



# Author
SARRAN SB
sbsarran@gmail.com
LinkedIn | GitHub

# If you found this useful, consider giving a star!

If you want, I can also:


Create a perfect GitHub repo structure with code templates


Write a resume project description (ATS optimized)


Help you deploy this on AWS/GCP step-by-step

