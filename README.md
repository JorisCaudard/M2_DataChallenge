# Data Challenge

Repository exploring various method of supervised learning on two different problem : Regression and Classification. 


## Description

Data challenges :

* [NYC Taxi tips](https://www.kaggle.com/competitions/nyc-taxis-tips)
* [Forest Cover type](https://www.kaggle.com/competitions/forest-cover-type-orsay)

Each notebook is associated with one of those kaggle competitions, and each describes our process to build and implement various models to solve each of those challenges. More details is provided in each notebook

## Getting Started

### Requirements

* Python 3.13 (recommended)
* numpy 1.26.4 (recommended, might cause issues with seaborn with )
* matplotlib 3.9.2
* seaborn 0.13.2
* folium 0.1.5
* scikit-learn 1.5.2
* xgboost 2.1.2

### Project Structure

- Data/
    - Classification/
    - Regression/
- Notebooks/
    - Classification.ipynb
    - Regression.ipynb
-README.md

### Usage

Both notebooks can be ran as is. You can also sepcify a custom dataset directory for each notebook in the *Loading Data* part of each notebooks to specify a custom dataset path and custom file name.

Note that in order for the notebook to correctly run, both dataset directory must contain :
- a train file, named train.parquet for the Regression notebook and train.csv for the Classification notebook ;
- a test file, named test.parquet for the Regression notebook and test.csv for the Classification notebook ;
- a naive submission with the correct format and type.

## Authors


* [CAUDARD Joris](https://github.com/JorisCaudard)
* [PASQUIER Thomas](https://github.com/Lanouraf)