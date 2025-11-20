# Public Sentiment Analysis on Shipping Discount Regulation  
Analysis of TikTok Comments Related to Permen Komdigi No. 8 Tahun 2025  
*(Dataset: 5,967 TikTok Comments)*

This project analyzes public sentiment and discussion patterns regarding the Indonesian government's shipping discount limitation policy (Permen Komdigi No. 8/2025). Using Natural Language Processing techniques, the study reveals how the public reacts to the restriction of free shipping promos and how the conversation evolves over time.

---

## 📌 Background  
In 2025, the Ministry of Communication and Digitalization (Komdigi) issued a new regulation limiting free-shipping discounts to **a maximum of 3 days per month**.  
This led to strong reactions from the public, especially online shoppers and couriers affected by the policy.

Understanding public sentiment is crucial to evaluate:
- Public acceptance or rejection,
- Impact on consumer behavior,
- Perception of the government and logistics ecosystem.

---

## 📊 Dataset  
- **Total comments analyzed:** 5,967  
- **Source:** TikTok comment section  
- **Period:** May–June 2025  
- Dataset includes opinions, reactions, and responses to the shipping-policy announcement.  
:contentReference[oaicite:0]{index=0}

---

## 🔧 Methods Used  
### **1. Sentiment Analysis**  
Classified each comment into:
- Positive  
- Neutral  
- Negative  

Sentiment distribution (from the PPT):
- **Negative:** 55%  
- **Neutral:** 38%  
- **Positive:** 6%  
:contentReference[oaicite:1]{index=1}

### **2. Wordlink / Bigram Network Analysis**  
Extracted frequent word associations to understand narrative patterns in:
- Positive sentiment  
- Negative sentiment  
- Neutral sentiment  
:contentReference[oaicite:2]{index=2}

### **3. Topic Modeling**  
Generated topics for:
- Positive comments  
- Negative comments  
- Neutral comments  

Helps identify dominant themes (e.g., cost concerns, courier welfare, offline shopping preferences).  
:contentReference[oaicite:3]{index=3}

### **4. Trend Analysis**  
Tracked comment volume and sentiment over time:
- Sharp spike on **20–21 May 2025**  
- Decline after announcement  
:contentReference[oaicite:4]{index=4}

---

## 📈 Key Findings  

### **1. Sentiment Dominance**
- The public reaction is **mostly negative (55%)**, indicating broad disagreement with the policy.  
- Positive sentiment is minimal, mostly from offline sellers or logistics workers.  
:contentReference[oaicite:5]{index=5}

### **2. Main Themes Identified**
#### **Positive Topics**
- Cost-saving opportunities  
- Support for offline stores  
- Empathy for courier welfare  
:contentReference[oaicite:6]{index=6}

#### **Negative Topics**
- Increased financial burden on buyers  
- Decreasing online shopping activity  
- Concerns about courier income  
- Criticism towards government policy  
:contentReference[oaicite:7]{index=7}

#### **Neutral Topics**
- Ordinary discussions about packages/transactions  
- Comments unrelated to the policy (noise)  
- General observations about delivery interactions  
:contentReference[oaicite:8]{index=8}

### **3. Public Engagement**
Several influencers drive significant negative engagement on TikTok, amplifying criticism.  
:contentReference[oaicite:9]{index=9}

---

## 🧠 Conclusion  
The limitation of free-shipping promotions triggered **predominantly negative sentiment** and sparked concerns about rising costs and courier impact.  
Although some users see benefits for offline stores, the majority express dissatisfaction or confusion.

These insights highlight a **gap between policy goals and public understanding**, suggesting the need for improved communication and mitigation strategies.

---

## 💡 Recommendations  
Based on the findings:
- Improve public communication about the policy purpose  
- Provide support mechanisms for couriers/logistics workers  
- Encourage local/traditional markets  
- Collaborate with e-commerce platforms for balanced solutions  
- Monitor public reaction continuously  
:contentReference[oaicite:10]{index=10}

---

## 🛠️ Tech Stack  
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- NLTK / spaCy  
- Gensim (Topic Modeling)  
- Matplotlib / Seaborn  

---

## 📬 Contact  
Feel free to reach out for discussion or collaboration:

**Ahmad Fauzan**  
GitHub: https://github.com/afauzan14  
LinkedIn: <your LinkedIn URL>

---

## ⭐ Acknowledgement  
This analysis is based on sentiment extraction and topic modeling from the presentation provided in this repository.  
