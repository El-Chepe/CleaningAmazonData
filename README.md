# CleaningAmazonData

This python package used to clean scraped amazon data. It has been built as part of 'CrowdDoing: Medicinal Food App development project'.

Large amount of relevant medicinal food data has been scraped from amazon. It is messy and data scientist coworker need to clean it everytime before analysis or model development phase. This package offer easy data cleaning by just 2-3 line of code. It has following features:

* clean inappropriate data in column and casting them to appropriate format
* removes duplicated rows
* handle missing value 
* Checking ASIN in appropriate form. Displays inappropriate ASIN form.
* Removes unnecessary rows
* Additionaly some feature engineering work. It adds following columns to dataframe
  1. 'category' - define category of product
  2. 'ProcessedText' - Cleaned text with basic text preprocessing (remove stopwords, punctuation, digits, non-english character and lemmatize verb) applied to 'ReviewContent' field
 * Can be integrated with sklearn pipeline
  
## Installation

### Requirements
  
#### Create a virtual environment
First install virtualenv on your machine if that it is not already the case:

`pip install virtualenv`

Then create the virtual env on you local machine:

`virtualenv -v env`

Finally active your newly created virtual environment:
  
`source env/bin/activate`
  
#### Install requirements
Once you activated your virtual enviromnent, you need to install all the Python packages that are required to run such datapipeline:

`pip install -r requirement.txt`

#### Install package

``` pip install git+https://github.com/LajariAlandkar/CleaningAmazonData.git```

## Usage
For usage, follow example.ipynb file


  
