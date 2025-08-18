# 🖼️ Image Captioning using Deep Learning

This project implements **automatic image captioning**, combining **CNN-based encoders** and **RNN/Transformer-based decoders** to generate natural language descriptions for images. The model is trained on the **Flickr8k and Flickr30k datasets**.

## 🚀 Features
- CNN encoder (ResNet/VGG) for **visual feature extraction**.
- RNN decoder (LSTM/GRU) and Transformer for **sequence generation**.
- Preprocessing pipeline: tokenization, vocabulary building, and caption encoding.
- Trained using **teacher forcing** for efficient convergence.
- Evaluated with **BLEU-1 to BLEU-4 scores** to measure caption quality.

## 🛠️ Tech Stack
- Python, PyTorch  
- CNN (ResNet/VGG)  
- RNN (LSTM/GRU) & Transformer  
- NLTK (for tokenization, BLEU)  

## 📂 Datasets
- **Flickr8k**  
- **Flickr30k**

## 📊 Results
- Generated captions were **semantically relevant and grammatically coherent**.  
- BLEU-4 scores demonstrated the effectiveness of both **CNN+RNN** and **Transformer-based approaches**.

## ▶️ Usage
```bash
# Clone repo
git clone https://github.com/TrivikramUmanath/Image-Captioning-using-Deep-Learning.git
cd Image-Captioning-using-Deep-Learning

# Open notebook and train
jupyter notebook
