🛒 Product Review Sentiment Analysis
BERT + BiLSTM Based NLP System
📌 Project Overview

This project is an end-to-end Natural Language Processing (NLP) application designed to analyze and classify sentiment from product reviews. The system leverages a hybrid BERT + BiLSTM deep learning architecture to capture both contextual semantics and sequential dependencies in textual data.

The complete pipeline covers data preprocessing, vectorization, model training, evaluation, and real-time inference through an interactive frontend interface.

🎯 Objectives

Analyze real-world product reviews and classify sentiment accurately

Compare the performance of multiple word embedding techniques

Implement a hybrid transformer + sequential deep learning model

Build a working frontend for real-time sentiment prediction

Deliver a clean, modular, and reproducible ML pipeline

🧠 Model Architecture

The core model is a BERT + BiLSTM hybrid architecture, where:

BERT is used for generating rich contextual embeddings

BiLSTM captures long-range dependencies and word order information

Fully connected layers perform final sentiment classification

🧩 System Pipeline
Raw Product Reviews
        ↓
Text Preprocessing
        ↓
Vectorization & Embedding Generation
        ↓
BERT + BiLSTM Model Training
        ↓
Model Evaluation (Accuracy, Loss, Confusion Matrix)
        ↓
Real-time Sentiment Prediction (Frontend)

🧪 Embedding Techniques Used

The model was trained and evaluated using three different embedding strategies:

Transformer-based embeddings (BERT)

Additional word embedding techniques for comparative analysis

This allowed performance comparison in terms of convergence behavior, accuracy, and generalization.

📊 Evaluation Metrics

The model was evaluated using:

Training & Validation Accuracy

Training & Validation Loss

Confusion Matrix

Classification Performance on unseen reviews

All trained models demonstrated strong convergence, low loss, and high sentiment classification accuracy.

🖥️ Frontend Interface

The project includes a fully functional frontend interface that allows users to:

Enter product reviews in real time

Receive instant sentiment predictions

Interact with the trained NLP model seamlessly

The frontend is directly connected to the trained model for live inference.

🛠️ Technologies & Tools

Programming Language: Python

Deep Learning: TensorFlow / Keras

NLP: Transformers (BERT), BiLSTM

Data Processing: NumPy, Pandas

Visualization: Matplotlib, Seaborn

Frontend: Custom UI for real-time predictions

📂 Project Structure
├── data/
│   ├── raw_reviews.csv
│   └── processed_reviews.csv
│
├── models/
│   ├── bert_bilstm_model.h5
│
├── notebooks/
│   ├── preprocessing.ipynb
│   ├── training.ipynb
│   └── evaluation.ipynb
│
├── frontend/
│   ├── app.py
│   └── ui_components/
│
├── requirements.txt
└── README.md

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/product-review-sentiment-analysis.git


Install dependencies:

pip install -r requirements.txt


Run the frontend application:

python frontend/app.py


Enter a product review and receive a sentiment prediction.

📌 Key Features

End-to-end NLP pipeline

Hybrid BERT + BiLSTM architecture

Multiple embedding techniques comparison

Real-time sentiment prediction

Clean and modular codebase

Ready-to-use trained model

📚 Learning Outcomes

Hands-on experience with transformer-based NLP models

Understanding hybrid deep learning architectures

Model evaluation and performance analysis

Practical ML system integration with frontend

End-to-end ML project deployment workflow

🤝 Acknowledgments

I would like to express my gratitude to my instructors and seniors for their guidance and support throughout the development of this project.

📜 License

This project is intended for educational and research purposes.
