# 💬 Text Sentiment Analysis from Social Media

## 📘 Overview
In the digital era, people express their emotions and opinions across social media platforms, blogs, and review sites. Analyzing this data manually is time-consuming and inefficient.  
This project presents a **Python-based Sentiment Analysis tool** that uses the **VADER (Valence Aware Dictionary and sEntiment Reasoner)** model from the **NLTK** library, integrated with a **Tkinter-based GUI**.  

The system classifies user-input text as **Positive**, **Negative**, or **Neutral**, providing real-time feedback with color-coded outputs and emojis.

---

## 🎯 Objectives
- Develop a **desktop sentiment analysis application** using Python.  
- Implement **rule-based sentiment classification** using the VADER lexicon.  
- Design a **Graphical User Interface (GUI)** for user interaction via Tkinter.  
- Display classification results with **color coding and emojis**.  
- Demonstrate a simple and fast **NLP-based opinion mining tool** for educational use.

---

## 🧠 Methodology

### 🔹 Workflow
1. **Input Collection** – Users enter text through the GUI.  
2. **Preprocessing** – The text is converted to lowercase and tokenized.  
3. **Valence Lookup** – Each word’s sentiment score is retrieved from the VADER lexicon.  
4. **Score Aggregation** – Individual word scores are summed.  
5. **Normalization** – A compound score is calculated (range: -1 to +1).  
6. **Classification** – Sentiment is categorized as:
   - Positive (≥ 0.05)
   - Negative (≤ -0.05)
   - Neutral (between -0.05 and 0.05)
7. **Output Presentation** – Results are displayed with color codes and emojis.

---

## 🧩 System Architecture

### Components:
- **Frontend (Tkinter):** User input and output display interface.  
- **Backend (Python + NLTK):** Handles text analysis and sentiment computation.  

**Libraries Used:**
- `nltk` — For VADER sentiment lexicon and NLP functions  
- `tkinter` — For GUI interface  
- `re` — For text tokenization  
- `math` — For compound score normalization  

---

## ⚙️ Technologies Used
| Component | Description |
|------------|-------------|
| **Language** | Python |
| **Libraries** | NLTK, Tkinter, re |
| **Model** | VADER (Valence Aware Dictionary and sEntiment Reasoner) |
| **Interface** | Tkinter-based Desktop GUI |
| **Development Environment** | Jupyter Notebook / PyCharm |

---
# Result
<img width="1080" height="352" alt="image" src="https://github.com/user-attachments/assets/a470a539-2da0-4e83-829a-a440e56a761d" />
<img width="1071" height="341" alt="image" src="https://github.com/user-attachments/assets/4d2d7519-7920-48b9-9a90-c0edcd5319f6" />




