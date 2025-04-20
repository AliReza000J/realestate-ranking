# **Real Estate Listings Ranking using NLP, ML & LLM**

A full pipeline project to **rank anonymized Persian real estate ads** using a combination of structured features, LLM-based text embeddings, and machine learning models.

---

## 🌟 Project Goals

Democratize access to **Persian NLP** resources.

Build a public benchmark for ranking real estate ads.

Combine machine learning + text understanding for quality scoring.

---

## 💡 Use Cases

Rank and filter listings by quality, trust, and clarity.

Build better recommendation systems for property tech (PropTech).

Analyze seller writing styles and ad effectiveness.

Enable AI-driven search and summarization of property ads.

---

## 📦 Dataset

✅ 1 million anonymized real estate listings in Persian

✅ Text descriptions, numeric fields (price, area, region, etc.)

✅ Publicly available on [HuggingFace](https://huggingface.co/datasets/divaroffical/real_estate_ads) by **Divar**

---

## 🧠 What This Project Does

| Phase            | Description                                 |
|------------------|---------------------------------------------|
| 1. Data Cleaning | Load raw CSVs, clean text and numbers       |
| 2. Data Visualization | Visualize data for EDA
| 3. Feature Extraction | Extract structured features & price metrics |
| 4. Embeddings     | Use BERT to generate text embeddings       |
| 5. Writing Style  | Cluster seller styles (optional)           |
| 6. Proxy Labeling | Create synthetic ranking scores            |
| 7. Modeling       | Train model to predict scores              |
| 8. Ranking        | Sort ads by predicted rank                 |
| 9. Streamlit App  | UI for ranking and exploring listings      |

---

## 🛠 Technologies Used

```

Python 3.10+

Pandas / Numpy / Scikit-learn for data processing

Transformers (HuggingFace): for extracting Persian BERT embeddings

XGBoost / MLP / RandomForest: ranking models

Streamlit: front-end for search and display

SHAP (optional): to interpret model predictions

```

---

## 📁 Project Structure

```

realestate_ranking/
├── data/                  # Raw + cleaned data
├── src/                   # Source code
│   ├── preprocess.py      # Cleaning and preprocessing functions
│   ├── features.py        # Numeric feature engineering
│   ├── embeddings.py      # Extracting text embeddings
│   ├── clustering.py      # Writing style clustering (optional)
│   ├── modeling.py        # ML model training
│   ├── ranker.py          # Ranking pipeline
├── notebooks/             # Jupyter notebooks per phase
├── app/                   # Streamlit UI app
├── models/                # Saved model files
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation

```

---

## ⚙️ Installation

```

git clone https://github.com/AliReza000J/realestate-ranking

cd realestate-ranking

pip install -r requirements.txt

```

---

## 🚀 Quickstart

Run the Streamlit app after training:

```

streamlit run app/app.py

```

---

## 🤝 Contributions

Pull requests, ideas, and collaborations are welcome!

---

## 📜 License

MIT License.

---

## 📬 Contact

Built with ❤️ to empower the Persian AI community.

Feel free to reach out on GitHub or [AlirezaAbri61@gmail.com].
