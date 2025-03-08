# SMS Spam Classifier

This project builds a **machine learning model** to classify SMS messages as spam or ham using text processing techniques.

## Features
- **Text Preprocessing:** Uses NLP techniques for text cleaning.
- **Feature Extraction:** Converts text into numerical format using `CountVectorizer`.
- **Machine Learning Models:** Implements multiple classifiers:
  - **Logistic Regression**
  - **Decision Tree Classifier**
  - **K-Nearest Neighbors (KNN)**
  - **Naïve Bayes**
  - **Gradient Boosting**
  - **AdaBoost**
  - **Bagging & Extra Trees Classifier**
- **Model Evaluation:** Assesses performance with accuracy metrics.

## Technologies Used
- **pandas** (Data manipulation)
- **numpy** (Numerical operations)
- **scikit-learn** (ML model training & evaluation)
- **NLTK** (Text preprocessing)

## Installation
Install the required dependencies:
```bash
pip install pandas numpy scikit-learn nltk
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/yourusername/SMS-Spam-Classifier.git
cd SMS-Spam-Classifier
```
2. Run the Jupyter Notebook:
```bash
jupyter notebook SMS_Spam_Classifier.ipynb
```
3. Follow the notebook instructions to train models and classify messages.

## Example Output
- **Input:** SMS text message
- **Output:** Predicted label (Spam or Ham)

## Contributing
Feel free to submit issues or pull requests to improve this project.
