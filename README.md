# 📰 Fake News Classification using Machine Learning

This repository contains a Google Colab notebook for detecting **fake news** using various machine learning algorithms. The models are trained on the **Fake_News_Detection** dataset.
Kaggle: https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets
## 📚 Overview

The project compares the performance of the following classifiers:

- 🔹 Naive Bayes
- 🔹 Support Vector Machine (Linear Kernel)
- 🔹 Support Vector Machine (RBF Kernel)

The dataset includes real and fake news articles, and the models learn to classify based on textual features (e.g., TF-IDF).


## 🧠 Models Used

| Model                  | Description                                       |
|------------------------|---------------------------------------------------|
| Naive Bayes            | Probabilistic model, simple and fast              |
| SVM (Linear Kernel)    | Good for linearly separable data                  |
| SVM (RBF Kernel)       | Handles non-linear boundaries using RBF function  |

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score

> You can also visualize performance using classification reports and plots.

---

## 📌 Requirements

The notebook uses the following Python libraries:

- `pandas`
- `numpy`
- `sklearn`
- `re`
- `missingno`

Colab already has these pre-installed.

---

## 📷 Sample Results

| Model | Accuracy |
|-------|----------|
| Naive Bayes | 0.93 |
| SVM (Linear) | 0.993 |
| SVM (RBF) | 0.994 |

*(These are hypothetical results; update based on your real output)*

---

## 🙋 Author

**Baohikari**  
📫 [GitHub Profile](https://github.com/Baohikari)
