# Text Generation using LSTM and GRU

## 📌 Project Overview

This project demonstrates text generation using two popular Recurrent Neural Network (RNN) architectures: **Long Short-Term Memory (LSTM)** and **Gated Recurrent Unit (GRU)**. Both models are implemented using TensorFlow/Keras and trained to learn textual patterns from a dataset, enabling them to generate meaningful text based on a given input sequence.

The project provides a comparison of the two architectures in terms of learning capability, training efficiency, and text generation performance.

---

## 🚀 Objectives

- Understand sequence modeling using Recurrent Neural Networks.
- Implement text generation using LSTM and GRU architectures.
- Compare the performance of LSTM and GRU models.
- Generate coherent text from a seed input.

---

## 📂 Project Files

- **LSTM_Text_Generation.ipynb** – Implementation of text generation using stacked LSTM layers.
- **GRU_Text_Generation.ipynb** – Implementation of text generation using stacked GRU layers.

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Google Colab / Jupyter Notebook

---

## 🧠 Model Architectures

### LSTM Model
- Embedding Layer
- Stacked LSTM Layers
- Dense Output Layer
- Optimized using RMSprop optimizer
- Sparse Categorical Crossentropy Loss

### GRU Model
- Embedding Layer
- Stacked GRU Layers
- Dense Output Layer
- Optimized using RMSprop optimizer
- Categorical Crossentropy Loss

---

## ⚙️ Workflow

1. Load and preprocess the text dataset.
2. Convert characters into integer sequences.
3. Create input-target sequence pairs.
4. Build and train the LSTM and GRU models.
5. Generate text using a user-provided seed string.
6. Compare the performance of both models.

---

## 📊 Comparison

| Feature | LSTM | GRU |
|---------|------|-----|
| Memory Mechanism | Memory Cell | Hidden State |
| Gates | Input, Forget, Output | Update, Reset |
| Number of Parameters | Higher | Lower |
| Training Speed | Slower | Faster |
| Long-Term Dependency Learning | Excellent | Very Good |

---

## 🎯 Applications

- Text Generation
- Story Generation
- Poetry Generation
- Language Modeling
- Chatbots
- Natural Language Processing (NLP)

---

## 📈 Results

- Successfully trained LSTM and GRU models for text generation.
- Both models learned sequential patterns from the dataset and generated coherent text.
- LSTM achieved strong performance in capturing long-term dependencies.
- GRU provided faster training while maintaining competitive text generation quality.

---

## 🔮 Future Enhancements

- Integrate Attention Mechanism
- Implement Transformer-based text generation
- Experiment with larger datasets
- Deploy using Flask or Streamlit

---

## 👨‍💻 Author

**KanakaRaju Simhadri**

AI & Machine Learning Enthusiast | Deep Learning | NLP | TensorFlow

---
