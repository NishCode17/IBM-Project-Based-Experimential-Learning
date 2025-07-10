# 📰 Fake News Generator and Detector

## 📌 Overview  
This project is a dual-purpose tool focused on both **generating** and **detecting** fake news. It’s built to explore the rise of misinformation online and provides an educational platform to understand how fake content is created and identified using machine learning techniques.

---

## The Problem it Solves  
Fake news has become a major threat in today's digital era. From influencing elections to spreading medical misinformation, fake news causes confusion, division, and sometimes even harm.  
This project helps tackle the issue in two ways:

1. **Fake News Generator** – By simulating how fake articles can be generated, users get a hands-on look at how deceptively real they can appear.
2. **Fake News Detector** – Provides a tool that classifies news articles as *real* or *fake*, helping users and developers build awareness around spotting misinformation.

---

## Models Used and Why

### 🔹 Fake News Generator – GPT-2  
We used OpenAI’s **GPT-2** language model to generate synthetic news articles. GPT-2 was chosen because:
- It has strong text generation capabilities.
- It’s open-source and student-friendly.
- It helps demonstrate how easily fake content can be created by AI.

### 🔹 Fake News Detector – BERT  
For the detection task, we used **BERT** (Bidirectional Encoder Representations from Transformers). It’s widely recognized for its performance in NLP classification tasks. Key reasons for choosing BERT:
- It understands context deeply by reading text bidirectionally.
- It’s pre-trained and fine-tunable, saving both time and compute.
- It has shown state-of-the-art performance in fake news classification tasks.

---

## Tech Stack  
- Python  
- Hugging Face Transformers  
- Gradio (for UI)  
- Jupyter Notebooks

---

## How to Use  
1. Run the notebook  
2. Input any news text or let the generator create one.  
3. Use the detector to classify it as *real* or *fake*.  
