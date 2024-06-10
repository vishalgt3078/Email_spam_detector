# Email_spam_detector

## Overview
This project aims to classify emails as spam or ham (non-spam) using the Naive Bayes classifier. It utilizes the `sklearn` library in Python for data preprocessing and modeling.

## Dependencies
Make sure you have the following dependencies installed:
- pandas
- numpy
- scikit-learn (`sklearn`)

You can install them using pip:
```
pip install pandas numpy scikit-learn
```

## Usage
1. **Clone the Repository**: Clone this repository to your local machine.
2. **Install Dependencies**: Ensure that all required dependencies are installed as mentioned above.
3. **Data Preparation**: 
   - Prepare your dataset in CSV format. This code assumes you have a dataset named "spam.csv" with a 'Message' column containing email text and a 'Category' column indicating whether the email is spam or ham.
4. **Model Training and Testing**:
   - Run the provided Python script.
   - The script will read the dataset, preprocess the data, train the Naive Bayes classifier, and test the model's accuracy.
5. **Real-time Prediction**:
   - You can test the trained model with new email examples.
   - Modify the `email_ham` and `email_spam` lists with your own email examples and run the corresponding prediction code.
6. **Experiment and Evaluation**:
   - Experiment with different feature extraction techniques or classifiers to improve the model's performance.
   - Evaluate the model's accuracy on the test set to assess its effectiveness.

## Example
Here's a simple example of how to use the provided code:

```bash
# Run the provided Python script spam_classifier.py
python spam_classifier.py
```

