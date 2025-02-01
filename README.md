# **Abstractive Urdu Text Summarization Using Deep Learning**

## **Overview**
This project focuses on abstractive text summarization for Urdu using deep learning models to generate concise, coherent summaries of large Urdu texts. The goal is to improve the quality of Urdu summarization using transformer-based architectures, specifically **mBART**, fine-tuned on a large dataset of Urdu news articles.

## **Key Features**
- **Deep Learning Models**: Utilizes **mBART** and **mT5** for abstractive summarization of Urdu texts.
- **Golden Dataset**: Fine-tuned using a **golden dataset** of 875 manually validated Urdu summaries, ensuring high accuracy and coherence.
- **Dataset**: Trained on **64,000 Urdu news articles**, with manually validated summaries for optimal training.
- **Evaluation Metrics**: Summaries evaluated using **BERTScore**, which measures the semantic similarity between generated and reference summaries, ensuring that the generated summaries are not only fluent but also contextually relevant.
- **Challenges**: Overcomes dataset scarcity and handles the complexities of Urdu text for summarization.

## **Objectives**
- Implement deep learning techniques for high-quality Urdu text summarization.
- Fine-tune **mBART** and **mT5** models to improve Urdu summarization.
- Generate summaries that capture the essence of the original content while ensuring fluency and coherence.

## **Results**
- **BERTScore**: The generated summaries achieved an average **BERTScore** of **0.497** for **mBART**, highlighting significant semantic similarity and coherence when compared to reference summaries.
- **Performance**: **mBART** outperformed **mT5** in terms of fluency, coherence, and context, producing more human-like summaries.

## **Hyperparameters (for mBART)**
- **Learning Rate**: 3e-5
- **Batch Size**: 4
- **Number of Beams**: 5
- **N-Gram Size**: 2
- **Length Penalty**: 1.0
- **Epochs**: 2
- **Precision**: fp16
- **Max Tokens**: 1024

