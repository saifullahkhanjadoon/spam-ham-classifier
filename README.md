
# Spam Ham Classifier

A Machine Learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques.

---

## Project Overview

This project uses:

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* TF-IDF Vectorization
* Naive Bayes Algorithms

The model is trained on SMS message data and predicts whether a message is spam or ham.

---

## Features

* Data preprocessing and cleaning
* Duplicate and null value handling
* Text preprocessing using NLP
* Tokenization and stemming
* TF-IDF vectorization
* Spam/Ham prediction
* Model evaluation using accuracy and precision
* Comparison of multiple Naive Bayes models

---

## Technologies Used

| Technology   | Purpose                     |
| ------------ | --------------------------- |
| Python       | Programming Language        |
| Pandas       | Data Handling               |
| NumPy        | Numerical Operations        |
| Matplotlib   | Data Visualization          |
| NLTK         | Natural Language Processing |
| Scikit-learn | Machine Learning            |

---

## Machine Learning Models Used

The following models were tested:

* Gaussian Naive Bayes
* Multinomial Naive Bayes
* Bernoulli Naive Bayes

The project mainly uses:

```python
MultinomialNB()
```

because it performs best for text classification.

---

## Dataset

The project uses an SMS Spam Collection dataset.

Dataset columns:

* `v1` → target label (spam/ham)
* `v2` → message text

The columns were renamed to:

```python
v1 -> target
v2 -> text
```

---

## Project Workflow

1. Import dataset
2. Clean dataset
3. Remove duplicates
4. Encode labels
5. Perform text preprocessing
6. Apply TF-IDF vectorization
7. Split data into training and testing sets
8. Train machine learning models
9. Evaluate accuracy and precision
10. Predict spam or ham messages

---

## Installation

Clone the repository:

```bash
git clone https://github.com/saifullahkhanjadoon/spam-ham-classifier.git
```

Move into the project folder:

```bash
cd spam-ham-classifier
```

Install required libraries:

```bash
pip install -r requirements.txt
```

---

## Required Libraries

```python
numpy
pandas
matplotlib
nltk
scikit-learn
```

---

## Run the Project

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
spam_ham.ipynb
```

---

## Example Prediction

```python
message = "Congratulations! You won a free iPhone"
```

Output:

```text
SPAM
```

---

## Future Improvements

* Add Flask or Django web app
* Deploy model online
* Improve accuracy with advanced NLP
* Add real-time message prediction
* Create GUI interface

---

## Author

**Saifullah Khan Jadoon**

Student at COMSATS University Abbottabad Campus.

---

## License

This project is for educational and learning pu
