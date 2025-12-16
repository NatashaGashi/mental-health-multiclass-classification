# mental-health-multiclass-classification

Identifying Mental Health States and Disorders from online-based text data using multi-class machine learning models.  
Logistic Regression, Random Forest, Decision Tree, and Complement Naive Bayes were used and compared with feature extraction methods such as TF-IDF and Bag-of-Words to classify posts into seven mental health categories.

### Setup Notes
This project uses NLTK for text preprocessing.  
The following resources must be downloaded in order to run the notebook successfully.

---

## Environment and Dependencies

The Jupyter notebook was developed and executed using the following environment.

### Python Version
- Python 3.12.2 | packaged by conda-forge | Clang 16.0.6

### Python Packages
- pandas
- numpy
- scikit-learn
- imbalanced-learn
- nltk
- matplotlib
- seaborn
- jupyter

### NLTK Resources
The following NLTK resources are required and are downloaded at runtime:
- stopwords
- wordnet
- averaged_perceptron_tagger_eng
