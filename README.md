# 🎬 Movie Review Sentiment Analysis (LSTM)

A sentiment classification project on movie reviews, built toward an LSTM-based model. This repo currently contains the **data exploration stage** — model training is still to come.

---

## 📌 What's in `LSTM.ipynb` right now

| Step | What it does |
|---|---|
| Load data | Reads `movie_reviews.csv`, falls back to a 10-row dummy dataset if missing |
| Preview | Shows first 10 rows |
| Shape | Prints row/column counts |
| Missing values | Checks each column for nulls |
| Class balance | Bar chart of Positive vs Negative review counts |
| Class count | Prints number of unique sentiment labels |

> ⚠️ **Note:** No LSTM model exists in the notebook yet — this is EDA only. See roadmap below.

---

## 🚀 Quick Start

```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook LSTM.ipynb
```

Drop a `movie_reviews.csv` (columns: `review`, `sentiment`) in the same folder before running — otherwise a dummy dataset kicks in automatically.

---

## 🗺️ Roadmap

- [x] Load & explore dataset
- [ ] Clean & preprocess text
- [ ] Tokenize + pad sequences
- [ ] Train/test split
- [ ] Build LSTM model (Keras/TensorFlow)
- [ ] Train & evaluate
- [ ] Save model

---

## 🛠️ Stack
`Python` · `pandas` · `numpy` · `matplotlib` · `seaborn` · *(planned: TensorFlow/Keras)*

---

## 📄 License
MIT — update as needed.
