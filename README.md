# Indigo_Task
Overview

This project aims to develop a state-of-the-art question-answering (QA) model using the Quora Question Answer Dataset. The objective is to create an AI system capable of understanding and generating accurate responses to a variety of user queries, mimicking human-like interactions.

Key Steps

Data Preprocessing: Clean and preprocess the Quora dataset to ensure high-quality input for training the models.
Model Selection: Utilize pre-trained models like BERT for understanding context, T5 for text-to-text generation tasks, and GPT for generating human-like responses.
Training and Fine-tuning: Fine-tune these models on the Quora dataset to enhance their ability to answer questions accurately.
Evaluation: Assess the model’s performance using appropriate metrics such as accuracy, F1 score, and BLEU score.
Deployment: Deploy the model in a scalable environment to handle real-time queries efficiently.

Scalability

The approach outlined is highly scalable, designed to handle a large volume of queries and adapt to various domains. However, due to resource constraints, the full pipeline incorporating BERT, T5, and GPT models was not executed. The provided code is modular and can be scaled with the appropriate computational resources.

Limitations

Due to resource constraints, the complete pipeline incorporating BERT, T5, and GPT models could not be executed. The code provided is structured to facilitate easy integration and scalability once sufficient resources are available.

Tech Stack

Frontend

•	Not Applicable: This project focuses on backend development and does not include a frontend component.

Backend

•	Python: Primary programming language for developing the QA model.
•	Transformers Library: Provides state-of-the-art pre-trained models like BERT, T5, and GPT.
•	PyTorch: Deep learning framework used for model training and evaluation.
•	Datasets Library: Used for loading and preprocessing the Quora dataset.
•	Hugging Face: Provides pre-trained models and utilities for NLP tasks.

Additional Tools and Libraries

•	Pandas: For data manipulation and analysis.
•	NumPy: For numerical operations.
•	Scikit-learn: For data splitting and performance metrics.
•	Rouge-score: For evaluating generated answers using ROUGE metrics.
•	NLTK: For BLEU score computation and additional NLP utilities.

