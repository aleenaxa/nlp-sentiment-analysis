# Customer-sentiment-analysis-model

Binary sentiment classification of customer reviews using TF-IDF vectorisation 
and a Linear Support Vector Machine (SVM).

## Dataset
2,000 customer reviews from Amazon and Yelp (1,000 each), sourced from the 
UCI Machine Learning Repository. Labels are binary: positive (1) or negative (0).

## Approach
- Text preprocessing: lowercasing, punctuation removal, short token filtering
- Feature extraction: TF-IDF vectorisation (max 5,000 features, unigrams)
- Classifier: LinearSVC with regularisation parameter C=1
- Evaluation: accuracy, precision, recall, F1-score

## Results
| Model | Accuracy | F1-Score |
|---|---|---|
| Linear SVM | 84.5% | 84.6% |
| Logistic Regression | 83.0% | 82.8% |
| Naive Bayes | 81.8% | 81.6% |

## How to Run
Open the notebook in Google Colab:
https://colab.research.google.com/drive/1NHYUFVMRzgTRt5D20NQFuU0yCoK0TFSu#scrollTo=2x-M-gLy10eH

## Team
Aleena Akhter · Vishakya Dangalle · Afifa Marzana · Sara Khan · Sarah Zayba Ahamed

NLP Group Project
