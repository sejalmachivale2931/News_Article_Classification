# News_Article_Classification(NLP)
This project classifies news articles into multiple categories using Natural Language Processing.

### Dataset
- HuffPost News Dataset
- Features: headline + short_description
- Target: category (multi-class, imbalanced)

### Approach
- Text preprocessing using TF-IDF
- Logistic Regression classifier
- Handled class imbalance using class_weight
- Evaluated model using accuracy, precision, recall and F1-score

### Results
- Accuracy: ~56%
- Strong performance on major categories
- Improved recall and F1-score for minority classes

### Tech Stack
Python, scikit-learn, Pandas, NLP

