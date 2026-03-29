# LLM Fine-Tuning on Jane Austen Text

## 📌 Overview
This project focuses on fine-tuning a GPT-based language model (DistilGPT2) on text from Jane Austen’s novels using Hugging Face Transformers. The objective is to generate text that captures the style, tone, and structure of classic English literature, and to demonstrate how fine-tuning improves language generation quality over a base model.

---

## ▶️ Run this Notebook
https://colab.research.google.com/drive/1b1Ut9HmywSOQRcIcC5dIGERo1-wx_VZh?usp=sharing 

---

## 📝 What I Did
- Collected and cleaned text data from Project Gutenberg
- Preprocessed and tokenized text for training
- Fine-tuned a pre-trained DistilGPT2 model using Hugging Face Transformers
- Evaluated model performance using training loss and perplexity
- Generated and compared text outputs before and after fine-tuning

---

## 🛠️ Tech Stack
- Python  
- PyTorch  
- Hugging Face Transformers  
- Google Colab  

---

## 📊 Results
- Improved text coherence and grammatical structure after fine-tuning  
- Generated outputs reflect a more formal and literary writing style  
- Observed reduction in perplexity and training loss across epochs  

---

## 📊 Key Results
- Fine-tuned model produces more context-aware and stylistically consistent text than base DistilGPT2  
- Clear qualitative improvement observed in generated outputs  
- Demonstrates effectiveness of fine-tuning on domain-specific text data  

---

## 📝 Sample Outputs

### Example 1
Prompt: "Elizabeth Bennet walked into the room and"

**Before fine-tuning:**
Elizabeth Bennet walked into the room and asked her if she was going to be there.  
"I'm going to be there," she said.

**After fine-tuning:**
Elizabeth Bennet walked into the room and said,  
"I am sure you will not be surprised to hear that Mr. Bennet is not in the same room as you."

---

### Example 2
Prompt: "Mr. Darcy looked at Elizabeth and"

**Before fine-tuning:**
Mr. Darcy looked at Elizabeth and asked him if she was still there.  
"I'd love to go back to her," he said.

**After fine-tuning:**
Mr. Darcy looked at Elizabeth and said,  
"I am sure you will not be able to see her again."

---

## 📁 Project Structure
```bash
├── data/         # cleaned dataset
├── notebooks/    # training notebook
├── outputs/      # generated text samples
└── README.md
