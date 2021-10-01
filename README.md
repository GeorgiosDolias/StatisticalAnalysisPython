# StatisticalAnalysisPython

This repository contains the following python jupyter notebooks:

* (Medical_Data_Statistical_Analysis.ipynb) Statistical Analysis and creation of prediction models based on medical data from different datasets. Creation of Flask API in order to make predictions and test of http requests to the created via Postman.  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1WHkJ4lMhEWBsrdL1GPzito1TEGFG2sih)
* (Metorites_Impacts_Analysis.ipynb) Statistical analysis of a dataset about meteorites impacts in order to make predictions about a future strike on Earth. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1EY3l1grtaFwiJkzhETlDnzD_D7Yn-wKN#scrollTo=8745669b)
* (Dice_Statistical _Analysis.ipynb) Statistical analysis based on data generated from games that include dice and examination of their fair conditions.  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1bxDBo9m8cXGBNio_o7OVoReAjbHHmg2w)

## Reproducing Flask API of Medical_Data_Statistical_Analysis jupyter notebook

1. First, we create a virtual Python environment called: my_venv
```
  python3 -m venv my_venv
```
2. Then, we activate the virtual environment
```
source path_to_your_virtual_environment/bin/activate
```
3. After getting to the virtual environment's file, install prerequisite packages
```
wget https://raw.githubusercontent.com/GeorgiosDolias/StatisticalAnalysisPython/main/requirements.txt
```
and
```
pip install -r requirements.txt
```
4. Dowload and unzip contents from Github repo

Dowload and unzip contents from https://github.com/GeorgiosDolias/StatisticalAnalysisPython/archive/main.zip

5. Create API
```
python api.py
```


## Requirements

| Package | Version |
--- | ---
| flask | 1.1.2 |
| pandas |  1.1.3 |
| joblib | 1.0.1 |
| sklean | 0.23.2 |
