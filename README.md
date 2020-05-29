# Expedia Hotel Recommendations

This project is an implementation of Kaggle Expedia Hotel Recommendation [competition](https://www.kaggle.com/c/expedia-hotel-recommendations/overview) based on a multiclass classification approach. The approach develops 4 different models and then combines them through soft voting.

## Datasets
Before start, download the datasets from Kaggle and import them to `/datasets` folder in following format:
* `/datasets/train.csv`

## Installation
Model was developed with Python 3.7 version.
Use package manager [pip](https://pip.pypa.io/en/stable/) to install dependencies
```shell script
pip3 install -r requirements.txt
```

## Run

Run main python script to calculate recommendations. Output will be generated in the format of Kaggle submission file (Map@5) to `/datasets/test_results.txt`.
```shell script
python3 main.py
```
