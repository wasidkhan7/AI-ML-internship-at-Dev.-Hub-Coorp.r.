# Task 5: Mental Health Support Chatbot (Fine-Tuned)

## 🧠 Problem Statement
Fine-tune a language model to respond in an empathetic, emotionally supportive way to users struggling with stress, sadness, or anxiety.

## 🛠️ Solution
We fine-tuned `distilgpt2` using the `EmpatheticDialogues` dataset from Facebook AI. Training was done using Hugging Face’s Trainer API on a subset of 3,000–10,000 rows due to hardware limitations.

## 📦 Model Used
- `distilgpt2` (Fine-Tuned)

## 📊 Training Info
- Epochs: 1–2
- Batch Size: 2
- Platform: Google Colab (CPU)

## 🧪 Results & Findings
- The chatbot gives more emotionally appropriate responses
- Still limited in understanding deep context
- Better than prompt-based model for sensitive topics

## 📚 Skills Gained
- Fine-Tuning Language Models
- Tokenization & Formatting Text Datasets
- Trainer API (Hugging Face)
- Ethical considerations in chatbot design

## Note: I used distilgpt2 so the result might not be expected i could use mistral-7B but due to my system performance which doesnot align with the requirement of the model. 
