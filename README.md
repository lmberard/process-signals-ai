# Taller de Procesamiento de Señales (TA136), Introducción a la Inteligencia Artificial (TB056)

How to run it with vscode:

1. Create new scope
```bash 
python3.9 -m venv venv-taller
```

2. Activate virtual scope:
    on linux/Mac:
    ```bash 
    source venv-taller/bin/activate
    ```

    on Windows (cmd):

    ```bash 
    venv-taller\Scripts\activate
    ```

3. Install dependencies:

```bash 
pip install ipykernel notebook matplotlib pandas scikit-learn seaborn
```

4. Add scope as kernel for Jupyter

```bash 
python -m ipykernel install --user --name taller2025 --display-name "Python (Taller 2025)"
```


# 🧠 Machine Learning TP Collection

This repo contains all my practical assignments (TPs) for the *Taller de Procesamiento de Señales* course at Universidad de Buenos Aires.

The focus is on **Statistical Machine Learning** – which basically means using math, stats and probability to make machines learn from data without going full deep learning mode.

Each TP covers a different core topic. Here's a quick summary:

---

### 📌 TP Summaries

- **TP1 - Linear Regression**  
  Fit a line to predict continuous values. Super basic but fundamental.

- **TP2 - Polynomial Regression**  
  Same idea as TP1 but with curves. Adds complexity and risk of overfitting.

- **TP3 - Logistic Regression**  
  Classify things using probabilities (instead of just predicting numbers).

- **TP4 - Discriminant Analysis & KNN**  
  Learn how to classify using either statistical assumptions or neighbors.

- **TP5 - SVM (Support Vector Machines)**  
  Separate classes with the widest possible margin. Sounds fancy, is cool.

- **TP6 - Decision Trees & Random Forests**  
  Split data with "if-this-then-that" rules. Trees that vote.

- **TP7 - PCA (Principal Component Analysis)**  
  Reduce the number of variables while keeping the essence of the data.

- **TP8 - K-Means + EM (Expectation Maximization)**  
  Group data with or without soft probability assignments. Clustering time.

- **TP9 - NLP & Recommendation**  
  Predict the next word or suggest items. Includes some Word2Vec.

- **TP10 - Naive Bayes**  
  Simple but powerful classifier based on Bayes' theorem. Great for text.

- **TP11 - Variational Bayes for Gaussians**  
  Go full Bayesian and learn how to estimate distributions over parameters.

---

This course was awesome to understand ML from the ground up, without just relying on libraries. It mixes theory, code, and intuition really well.

Happy to share or discuss more if you're working on similar stuff!
