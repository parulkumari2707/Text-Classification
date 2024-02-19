Text Classification with Naive Bayes
===
This repository contains Python code for performing text classification using the Naive Bayes approach. The code utilizes the 20 Newsgroups dataset and applies a pipeline that includes feature extraction using TF-IDF or CountVectorizer and classification using Multinomial Naive Bayes.

Dataset
===
The dataset used in this project is the 20 Newsgroups dataset, which consists of approximately 20,000 newsgroup documents across 20 different categories. We focus on a subset of four categories: alt.atheism, soc.religion.christian, comp.graphics, and sci.med.

Requirements
===
+ To run the code, you need the following libraries installed:
  - scikit-learn
  - numpy
  - scipy

+ You can install the required libraries using pip:

```bash
pip install scikit-learn numpy scipy
```

Usage
====
1. Clone this repository to your local machine:
```bash
git clone https://github.com/parulkumari2707/Text-Classification.git
```
2. Navigate to the project directory:
``` bash
cd text-classification
```
3. Run the Python script text_classification.py to perform text classification using Naive Bayes:
```bash
python text_classification.py

```
Output
===
The output of the script includes the best hyperparameters found during grid search cross-validation, the best score achieved by the model on the training data, accuracy on the test set, and a detailed classification report containing precision, recall, F1-score, and support for each class.

License
===
This project is licensed under the [MIT License]. See the LICENSE(license) file for details.
