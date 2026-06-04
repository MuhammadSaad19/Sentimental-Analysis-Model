# Sentiment Analysis Model 🧠

A text classification model that categorizes input sentences into **Positive**, **Negative**, or **Neutral** sentiment using Facebook's BART transformer model.

---

## 📌 Overview

This project fine-tunes the **Facebook BART** model (an extension of BERT) on a large sentiment analysis dataset to classify text into three categories:
- ✅ Positive
- ❌ Negative
- ➖ Neutral

---

## 📊 Dataset

- **Source:** Kaggle
- **Size:** ~150,000 rows
- **Format:** Text + Sentiment Label

---

## 🏗️ Model

- **Base Model:** Facebook BART (facebook/bart-large-mnli)
- **Training Epochs:** 10
- **Accuracy:** ~97%
- **Model File:** `.pt` format (excluded due to size — download link below)

📥 **[Download Trained Model from Google Drive]**  *(https://drive.google.com/file/d/1cwnGd2f0TKdJc52ZrrEnwMrz5MNThZnr/view?usp=drive_link)*

---

## 🛠️ Libraries Used

| Library | Purpose |
|---|---|
| `transformers` | BART model loading and fine-tuning |
| `pandas` | Data loading and manipulation |
| `numpy` | Numerical operations |
| `scikit-learn` | Evaluation metrics |
| `matplotlib` | Plotting results |
| `seaborn` | Data visualization |
| `collections` | Data preprocessing utilities |

---

## 🚀 How to Run

**Step 1 — Install dependencies:**
```bash
pip install transformers pandas numpy scikit-learn matplotlib seaborn
```

**Step 2 — Train the model:**
```bash
python ML Model.ipynb
```
This will generate the `.pt` model file locally.



---

## 📁 Project Structure

```
Sentiment-Analysis-Model/
│
├── ML Model.ipynb          # Model training code
├── sentimant_data          # Training dataset
└── README.md
```



## 👨‍💻 Author

**Muhammad Saad Amir**
- GitHub: [MuhammadSaad19](https://github.com/MuhammadSaad19)
- LinkedIn: [muhammad-saad-amir](https://linkedin.com/in/muhammad-saad-amir)
