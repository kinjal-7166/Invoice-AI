# Invoice AI 🧾
### Smart Business Insights for Local Vendors

An end-to-end AI system that digitizes printed invoices using OCR and applies Machine Learning to generate actionable business insights — built specifically for small local vendors who rely on paper-based billing.

---

## 🚩 Problem Statement

Many small businesses like grocery shops, hardware stores, and general stores use printed invoices from POS printers or billing machines. Vendors store these in physical files with no easy way to search, calculate totals, or analyze sales trends. This project solves that by converting printed invoices into structured digital data and generating intelligent insights automatically.

---

## ✨ What It Does

| Module | Description |
|--------|-------------|
| 📷 **OCR Pipeline** | Extracts text from printed invoice images using TrOCR |
| 🧹 **Data Extraction** | Cleans and structures extracted text into CSV using Regex |
| 📊 **ML Analytics** | Applies ML models to generate sales insights |
| 🤖 **Virtual Assistant** | Answers simple business queries conversationally |
| 📈 **Dashboard** | Visualizes insights via Plotly charts in a Streamlit app |

---

## 🔍 ML Models Used

| Model | Purpose |
|-------|---------|
| **K-Means Clustering** | 4-cluster customer/product segmentation |
| **Random Forest** | Sales prediction |
| **Gradient Boosting** | Churn detection |

---

## 🛠️ Tech Stack

- **Language:** Python
- **OCR Model:** TrOCR (Hugging Face Transformers)
- **ML:** Scikit-learn (K-Means, Random Forest, Gradient Boosting)
- **Data Processing:** Pandas, NumPy, Regex
- **Visualization:** Plotly
- **Web App:** Streamlit
- **Notebook:** Jupyter Notebook

---

## 📁 Project Structure

```
Invoice-AI/
│
├── mini_project.ipynb    # Full pipeline: OCR → Data Extraction → ML → Insights
└── README.md
```

---

## 🔄 Project Workflow

```
Printed Invoice Images
        ↓
  TrOCR Model (OCR)
        ↓
  Regex Data Extraction
        ↓
  Export to CSV
        ↓
  ML Model Training
  (K-Means / Random Forest / Gradient Boosting)
        ↓
  Business Insights + Dashboard
```

---

## 📊 Insights Generated

- Daily earnings breakdown
- Product-wise sales performance
- Fast-moving and slow-moving item identification
- Customer segmentation
- Sales prediction and churn detection

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install transformers torch scikit-learn pandas numpy plotly streamlit
```

### Run the Notebook

1. **Clone the repository**
   ```bash
   git clone https://github.com/kinjal-7166/Invoice-AI.git
   cd Invoice-AI
   ```

2. **Open the notebook**
   ```bash
   jupyter notebook mini_project.ipynb
   ```

3. **Run all cells** in order — the notebook covers the full pipeline from OCR to ML insights.

---

## 🧠 Model Training Details

- **Dataset:** 2000+ annotated invoice images
- **Train/Test Split:** 80% train, 20% test
- **Evaluation:** Standard classification and regression metrics

---

## 💡 Key Highlights

- Solves a **real-world problem** for small vendors who cannot afford expensive ERP or billing software
- Uses a **transformer-based OCR model** (TrOCR) instead of traditional rule-based OCR
- Combines **Computer Vision + NLP + ML** in a single end-to-end pipeline
- Designed to be **simple and accessible** — no technical expertise required from the end user

---

## 🙋‍♀️ About

This project was built as an **academic project** during the pursuit of a PG Diploma in Artificial Intelligence & Machine Learning at MIT World Peace University, demonstrating a complete AI pipeline from raw image data to actionable business intelligence.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> ⭐ If you found this project helpful, consider giving it a star!
