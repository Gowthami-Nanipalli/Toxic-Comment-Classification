🛡️ Toxic Comment Classification using NLP
📌 Project Overview
This project focuses on detecting and classifying toxic comments using Natural Language Processing (NLP) and Deep Learning techniques. The model identifies different categories of toxicity such as abusive, offensive, threat, and identity-based hate comments.
The system is designed to help online platforms automatically filter harmful content and maintain healthy digital communication.
---
🎯 Problem Statement
Online platforms face challenges in moderating large volumes of user-generated content. Manual moderation is inefficient and time-consuming. This project builds an automated classification system to detect toxic comments accurately using deep learning models.
---
📊 Dataset
- Dataset: Kaggle Toxic Comment Classification Challenge
- Features include:
  - comment_text
  - toxic
  - severe_toxic
  - obscene
  - threat
  - insult
  - identity_hate
---
🧠 Technologies Used
- Python
- Google Colab
- Pandas & NumPy
- Scikit-learn
- TensorFlow / Keras
- LSTM (Long Short-Term Memory)
- BERT (Bidirectional Encoder Representations from Transformers)
---
⚙️ Model Architecture
🔹 LSTM Model
- Text tokenization
- Padding sequences
- Embedding layer
- LSTM layers
- Dense output layer with sigmoid activation
 🔹 BERT Model
- Pre-trained BERT model
- Fine-tuning for multi-label classification
- Improved contextual understanding
---
 📈 Results
- Achieved high accuracy in multi-label classification.
- BERT model performed better compared to traditional LSTM.
- Successfully classified toxic and non-toxic comments.
---
🔹How to Run
1. Install required libraries
2. Open the notebook in Google Colab
3. Run all cells sequentially
🔹 Future Improvements
- Deploy as web application
- Add REST API
- Improve performance with advanced transformers
