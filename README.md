# Sentiment Analysis with DistilBERT (TensorFlow) 🚀

This project implements **sentiment analysis** using the **pre-trained DistilBERT model** fine-tuned on the **SST-2 dataset**. It processes text inputs, tokenizes them, and classifies them as **positive or negative sentiments**.

---

## 📖 **Project Overview**
- Uses **Hugging Face's `transformers` library** to load a **pre-trained DistilBERT model**.
- Supports **single and batch sentence sentiment classification**.
- Converts **PyTorch models to TensorFlow** (if needed).
- Extracts **hidden states & attention weights** for interpretability.
- Saves and reloads the model and tokenizer for later use.

