Email Spam Classification

This project involves building a machine learning model to classify emails as spam or not spam (ham) using a provided dataset.

Dataset

The dataset (emails.csv) contains 5172 rows and 3002 columns. Each row represents an email, and the columns consist of:

Columns 1 to 3000: The count of the 3000 most common words in the emails (after excluding non-alphabetical characters/words).
First column: Email names (set with numbers to protect privacy).
Last column: Labels for prediction (1 for spam, 0 for not spam).

Usage

Dependencies

Python 3.x
pandas
scikit-learn

Installation

Clone the repository:
git clone https://github.com/ketanbhole/Spam-Classifier.git

Navigate to the project directory:
cd Spam-Classifier.git

Install the required libraries:
pip install -r requirements.txt

Running the Code
Place the emailst.csv file in the project directory.

Run the spam_classifier.py script:
python spam_classifier.py

Output
The script will output the accuracy of the trained model, a classification report, and a confusion matrix displaying performance metrics for spam classification.

Model Evaluation
The model achieves an accuracy of 95% on the test set, with precision, recall, and F1-score metrics detailed in the classification report.

Future Improvements
Experiment with different machine learning algorithms (e.g., Random Forest, Support Vector Machines) for potentially better performance.
Explore feature engineering techniques or additional preprocessing steps to enhance model accuracy.
