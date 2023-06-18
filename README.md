# Individualisierung von künstlich erzeugten Texten / Individualization of artificially generated texts

This repository contains Jupyter notebooks for the master thesis "Individualization of artificially generated texts".

## Content

### Crawl_Data.ipynb
This notebook presents how Reddit comments were extracted from the Pushshift Reddit dataset.
It also contains functionality to filter the data thus obtained according to certain criteria. Furthermore, the perplexity of the comments can be calculated

### Create_Formal_Style_Transfer.ipynb
Contains code to perform a formal style transfer using text-davinci-003

### Evaluate_Dataset.ipynb
Contains code to calculate the evaluation metrics of the dataset. Also contains code to visualize the calculated metrics

### Fine_Tune_Models.ipynb
Contains the code for fine-tuning various Transformer models using the dataset generated as part of the master's thesis.

### Evaluate_Models.ipynb
Contains code with which the models can be evaluated. By default, the models that were fine-tuned during the master thesis are used.

## Test_Models_Manually.ipynb
Contains code with which the models can be easily and quickly tested manually
