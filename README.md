# Coffee
## Overview
This project focuses on performing logistic regression analysis using a Jupyter Notebook. The core objective is to build a predictive model based on a given dataset and deploy it as a web application using Voila and Heroku.

## About Dataset
> Last month, British YouTuber (and former World Barista Champion) James Hoffman virtually hosted the Great American Coffee Taste Test, during which thousands of people simultaneously blind-tasted the same four coffees. Hoffman has published a video summarizing the results, as well as a spreadsheet of anonymized survey responses from 4,000+ participants. It includes tasters’ demographics, general coffee drinking habits and preferences, assessments of the four coffees, and more

[Coffee Tastings [Survey Analysis]](https://www.kaggle.com/datasets/sujaykapadnis/lets-do-some-coffee-tasting)


## Project Structure
- `notebooks/`: Contains the Jupyter Notebook (logistic_regression.ipynb) where the logistic regression analysis is performed.
- `data/`: Directory for storing the dataset used in the analysis.
- `models/`: Houses the serialized trained model (trained_model.pkl), if applicable.
- `requirements.txt`: Lists all necessary Python packages.
- `Procfile`: Used for deploying the web application on Heroku.

## Installation
Clone the repository:
```bash
git clone [repository-url]
```

Install required packages:
```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:
```bash
jupyter notebook
```

## Usage
Navigate to the notebooks/ directory and open logistic_regression.ipynb to view the analysis. The notebook includes detailed steps from data loading to model evaluation.

## Deployment
This project is configured for deployment with Voila and Heroku. Check Procfile for deployment commands.

