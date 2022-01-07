# SMS-Classification
## Model Evaluation and Validation
## Project: Spam vs Ham
### Install

This project requires Python and the following Python libraries installed:

1. NumPy
2. Pandas
3. matplotlib
4. scikit-learn
5. re
6. NLTK

You will also need to have software installed to run and execute a Jupyter Notebook.

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

### Code
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.
The files contain one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.
The data used is sms-spam-classification.csv .

### Run
In a terminal or command window, navigate to the top-level project directory boston_housing/ (that contains this README) and run one of the following commands:

```
ipython notebook SMS-Classification.ipynb
```
or open with Jupyter Lab
```
jupyter lab
```

This will open the Jupyter Notebook software and project file in your browser.


### Data

A collection of 425 SMS spam messages was manually extracted from the Grumbletext Web site. This is a UK forum in which cell phone users make public claims about SMS spam messages, most of them without reporting the very spam message received. The identification of the text of spam messages in the claims is a very hard and time-consuming task, and it involved carefully scanning hundreds of web pages.

#### Features

1. v1 contains the label (ham or spam) 
2. v2 contains the raw text.
