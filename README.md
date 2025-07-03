

# 📰 Fake News Detection using Machine Learning

This project aims to classify news articles as **real** or **fake** using Natural Language Processing (NLP) and machine learning. It uses a TF-IDF vectorizer with a Passive Aggressive Classifier to achieve high accuracy on labeled datasets.

---

## 🚀 Features

- Clean and preprocess real-world news datasets
- Text vectorization using TF-IDF
- Model training using PassiveAggressiveClassifier
- Evaluate model performance (accuracy & confusion matrix)
- Visualize confusion matrix as a heatmap
- Ready for deployment with Flask (optional)

---

## 📁 Dataset

- `Fake.csv` — Contains fake news articles  
- `True.csv` — Contains real news articles  
- These datasets are combined and labeled (`1` for fake, `0` for real)

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:**  
  - `pandas`, `numpy`  
  - `scikit-learn`  
  - `matplotlib`, `seaborn`  
- **Model:** Passive Aggressive Classifier  
- **Vectorizer:** TF-IDF (Term Frequency-Inverse Document Frequency)

---

## 📊 Model Evaluation

- **Accuracy:** ~93%
- **Confusion Matrix:** Displays True Positives, False Positives, etc.
- **Heatmap Visualization:** Helps understand model performance clearly

---
## 📷 Output Example

```text
Accuracy: 0.93
Confusion Matrix:
[[895   28]
 [ 45  801]]
```
---

## 🔮 Future Improvements

* Use deep learning models (LSTM, BERT)
* Add Flask-based web UI for real-time predictions
* Enhance text preprocessing (lemmatization, named entity removal)

---

## 🙋‍♂️ Author
TANMAY GUHA

Email:- tanmayguha15@gmail.com

---

## ⭐️ Show Some Love

If you find this useful, consider giving it a ⭐️ on GitHub and sharing it! Contributions welcome.

---

## 🏷️ License

This project is open-source and available under the [MIT License](LICENSE).

```


