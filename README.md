# SpamHam
SpamHam is a text-classification app which detects whether the message/email is spam or not. I've used Naive-Bayes along with NLP (TF-IDF, Bag of Words and more). <br>
In order to perform an experiment I've combined two datasets (Enron email spam/ham and SMS spam classification) into one to gather more data. 




### Built With

1. Django 2.1
2. Python 3.6
3. Scikit-Learn
4. Numpy
5. Pandas
6. Matplotlib
7. Seaborn
4. HTML5
5. CSS
6. Bootstrap-v4

### Installing/ Things you need to install the Web App and how to set up the project locally?

1. Python3
2. Pip
3. Django(2.1)
4. Conda

#### Steps
- Make a virtual environment using "conda create -n envname python=3.6 pip"
- source activate envname (for mac/linux) | activate envname (for windows)

- pip install -r requirements.txt
- Run the app using python manage.py runserver

### Milestones for version 2
- Implement login and tailor experience for each user
- Collect the result reported by user for false classification of messages/email
- Model will self-learn from the reported data



