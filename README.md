# WhatsApp Next Word Prediction using NLP

## Project Overview

This project focuses on building a **Next Word Prediction model** using **WhatsApp chat data**. By leveraging **Natural Language Processing (NLP)** techniques and **Deep Learning**, the model predicts the most likely next word based on a given sequence of words. The system is trained on real conversational data extracted from a WhatsApp chat text file.

The project demonstrates the complete NLP pipeline—from text preprocessing to sequence modeling using a neural network built with Keras.


## Dataset

* **Source**: WhatsApp Chat Export (`WhatsApp Chat.txt`)
* **Type**: Text data (conversational messages)
* **Content**: Real-world chat messages used to learn word patterns and sentence structures


## Technologies Used

* **Python**
* **TensorFlow / Keras**
* **Natural Language Processing (NLP)**
* **Tokenizer** (Keras)
* **Pad Sequences**
* **Sequential Model**
* **NumPy**
* **Matplotlib** (optional for visualization)


## Project Workflow

### 1. Data Loading

* Load WhatsApp chat text file (`WhatsApp Chat.txt`)
* Remove timestamps, usernames, and irrelevant symbols

### 2. Text Preprocessing

* Convert text to lowercase
* Remove special characters and extra spaces
* Prepare clean sentences for training

### 3. Tokenization

* Use **Keras Tokenizer** to convert words into numerical tokens
* Build vocabulary from chat data

### 4. Sequence Generation

* Create input sequences for next-word prediction
* Apply **Padding (Pad Sequences)** to ensure uniform input length

### 5. Model Building

* Build a deep learning model using **Sequential()**
* Embedding layer for word representation
* Dense output layer with softmax activation

### 6. Model Training

* Train the model on padded sequences
* Use categorical cross-entropy loss
* Optimize using Adam optimizer

### 7. Prediction

* Input a sentence fragment
* Model predicts the most probable next word


## Key Features

* Uses real WhatsApp chat data
* Implements Tokenization and Padding
* Deep Learning-based next word prediction
* Easily extendable to sentence generation


## Example Use Case

Input:

```
How are
```

Predicted Output:

```
you

## Conclusion

This project showcases how NLP and Deep Learning can be applied to real-world conversational data for next word prediction. It serves as a practical example for understanding sequence modeling and text-based neural networks.


⭐ If you found this project helpful, feel free to star the repository!
