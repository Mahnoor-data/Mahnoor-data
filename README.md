# Mahnoor Zakir

Data Science student building systems that solve real problems with data, NLP, and deep learning. Focused on production-ready projects with live demos and measurable impact.
<p align="center">
  <img alt="Python" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />
  <img alt="Pandas" height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" />
  <img alt="NumPy" height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" />
  <img alt="TensorFlow" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" />
  <img alt="PyTorch" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" />
  <img alt="SQL" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" />
  <img alt="Git" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
</p>
---

## About

I am a final-year DataScience student at University of Engineering and Technology Peshawar, specializing in data science and natural language processing. My work bridges traditional data analytics with modern AI — from Power BI dashboards for business insights to RAG-based systems for sensitive domains like religious text retrieval.

I build projects end-to-end: data collection, cleaning, modeling, deployment, and documentation. Every repository includes a live demo, professional README, and reproducible code.

---

## Technical Skills

| Category | Tools |
|----------|-------|
| **Languages** | Python, SQL |
| **Data & Analytics** | Pandas, NumPy, Matplotlib, Seaborn, Power BI, Excel |
| **Machine Learning** | TensorFlow, PyTorch, Scikit-learn |
| **NLP & LLMs** | HuggingFace Transformers, Sentence Transformers, LangChain, Groq |
| **Vector & Retrieval** | ChromaDB, FAISS, semantic search, RAG pipelines |
| **Deployment** | Hugging Face Spaces, Gradio, Streamlit |
| **Data Engineering** | API integration, PDF extraction, data pipeline design |
| **Generative AI** |


---

## Featured Projects

### QuranFiqah — RAG-Based Islamic Question Answering System

A production-deployed Retrieval-Augmented Generation system that answers Islamic jurisprudence questions using authenticated Quran, Hadith, and Tafseer sources. Constrains LLM output to retrieved content only — eliminating hallucination risks critical for religious guidance.

- **Architecture:** multilingual-e5-large embeddings + ChromaDB vector search + Llama 3.3 70B constrained generation
- **Corpus:** 36,606 documents (6,236 Quran verses, ~30,000 Hadith, 6,235 Tafseer entries)
- **Performance:** 3-4s response time, 100% source citation accuracy, 0% hallucination rate by design
- **Live Demo:** [huggingface.co/spaces/noormrc123/fiqah-qa](https://huggingface.co/spaces/noormrc123/fiqah-qa)
- **Repository:** [github.com/Mahnoor-data/QuranFiqah](https://github.com/Mahnoor-data/QuranFiqah)

Key technical decisions:
- Selected ChromaDB over Pinecone/Weaviate for zero-cost persistent storage
- Implemented batch embedding (64 docs/batch) to optimize Colab GPU utilization
- Designed strict system prompts with temperature=0.3 to prevent creative generation of religious rulings
- Handled real-world data engineering challenges: API failures, PDF OCR limitations, duplicate ID resolution

---

### Hinglish YouTube Sentiment Analysis

Deep learning comparison of RNN, LSTM, GRU, BiLSTM, and DistilBERT for sentiment classification of code-mixed Hinglish (Hindi-English) YouTube comments. Includes full data pipeline from collection to visualization.

- **Dataset:** 24,000 comments from 12 videos, balanced to 9,552 samples
- **Models:** RNN (65%), LSTM (72.1%), GRU (72.5%), BiLSTM (74%), DistilBERT (85%)
- **Key Finding:** BiLSTM delivers best accuracy-time ratio (74% in 9.9s); DistilBERT dominates accuracy but costs 28x training time
- **Techniques:** Automated RoBERTa labeling, stratified split, custom readability filters, professional matplotlib visualizations
- **Repository:** [github.com/Mahnoor-data/hinglish-sentiment](https://github.com/Mahnoor-data/hinglish-sentiment)

---

### E-Commerce Sales Insights — Blinkit Dataset

End-to-end retail analytics project analyzing consumer behavior, outlet performance, and product trends.

- **Tools:** Python (Pandas, NumPy), SQL, Power BI
- **Impact:** Identified Low Fat products = 64% of sales; Medium outlets = 44% revenue engine
- **Deliverable:** Interactive Power BI dashboard with drill-down capability
- **Repository:** [github.com/Mahnoor-data/E-Commerce-Sales-and-Insights](https://github.com/Mahnoor-data/E-Commerce-Sales-and-Insights)

---

### Customer Retention & Churn Analysis

Unified 7 relational tables into a customer model to identify churn drivers and retention opportunities.

- **Tools:** Power BI (DAX), SQL
- **Impact:** Discovered 104K churned customers causing 9.38% revenue loss; 147K at-risk customers identified
- **Key Drivers:** Order cancellations and late deliveries
- **Deliverable:** Power BI dashboard with churn risk segmentation
- **Repository:** [github.com/Mahnoor-data/Customer-Retention-and-Churn-Analysis](https://github.com/Mahnoor-data/Customer-Retention-and-Churn-Analysis)

---

### Marketing Campaign ROI & A/B Testing

Statistical evaluation of campaign effectiveness across channels and devices.

- **Tools:** Python (Pandas, Statsmodels), Power BI
- **Methods:** ANOVA, T-tests, CPA/ROAS/Profit Margin engineering
- **Finding:** Mobile CTR &gt; Desktop, but Desktop CVR and profitability stronger; Promos delivered highest ROAS (474%)
- **Deliverable:** Power BI dashboard for channel/device performance optimization
- **Repository:** [github.com/Mahnoor-data/Marketing-Campaign-ROI-A-B-Testing](https://github.com/Mahnoor-data/Marketing-Campaign-ROI-A-B-Testing)

---

## Education

**BS Datascience** — University of Engineering and Technology Peshawar, Pakistan

---

## Contact

- **Email:** noormrc123@gmail.com
- **LinkedIn:** [linkedin.com/in/mahnoor-zakir-9a6183358](https://www.linkedin.com/in/mahnoor-zakir-9a6183358?utm_source=share_via&utm_content=profile&utm_medium=member_android)
- **GitHub:** [github.com/Mahnoor-data](https://github.com/Mahnoor-data)

---

*Last updated: June 2026*
