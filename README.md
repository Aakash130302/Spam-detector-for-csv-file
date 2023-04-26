# Detect spam in csv file

User can upload csv file on the webpage to predict if it is spam or not.
User will be able to download predicted csv file to see spam/ham for individual text.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install streamlit.

```bash
pip install streamlit
```
Import all the dependencies such as pandas, numpy, csv, logistic regression, sklearn and pickle.
## How to start the webpage

Once you have imported all the required modules and libraries go to the folder in which you have these all files downloaded.
Then Open cmd in that folder. Now you can run the application on webpage using following command

```python
streamlit run "assign8.py"
```
## Usage
On the webpage user will be able to upload .csv file to check spam/ham. After uploading when user clicks on predict button model will predict spam/ham and provides a .csv file in which text is marked as spam or ham.
User can download this prediction file through webpage and can see their output.

## Preview of webpage
![prediction](https://user-images.githubusercontent.com/83350950/234586089-f33bac1a-3292-4e16-9441-8e8b685dd6f2.PNG)
