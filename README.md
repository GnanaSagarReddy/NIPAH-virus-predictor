# Nipah Virus Predictor

## Introduction

Nipah Virus Predictor is a machine learning project that aims to predict the likelihood of a person having the Nipah virus based on reported symptoms. The project leverages a dataset containing information about individuals with or without the Nipah virus, including symptoms such as fever, body pains, fatigue, sore throat, breathing difficulty, and cough.

## Features

- Predicts the likelihood of Nipah virus based on reported symptoms.
- Uses machine learning algorithms to analyze and classify input data.
- Provides an easy-to-use interface for users to input symptoms and receive predictions.


## Dataset

The project uses a dataset containing information about individuals with or without the Nipah virus. The dataset includes the following features:

- Fever
- Body pains
- Fatigue
- Sore throat
- Breathing difficulty
- Cough
To accomplish this, collecting data on various parameters such as age and symptoms of individuals affected by the Nipah virus is essential. Below is a sample dataset, randomly generated for illustrative purposes:

S.No. | Age (in years) | Body temp. (in °F) | Headache | Fever | Vomiting | Cough | Difficulty in breathing | Infected
:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
|1. | 38 | 99.42 | 1 | 0 | 1 | 0 | 0 | 0 |
|2. | 72 | 104.65 | 1 | 1 | 1 | 2 | 2 | 1 |
...
|10. | 65 | 102.69 | 1 | 1 | 1 | 1 | 1 | 1 |

**_Note:_**
* In the 'Headache,' 'Fever,' 'Vomiting,' and 'Infected' fields:
   0 – No
   1 – Yes
* For 'Cough' and 'Difficulty in breathing':
   0 – Not at all
   1 – Mild
   2 – Severe



## Machine Learning Model

The machine learning model employed in this project is based on Logistic Regression. The model has been trained on the provided dataset to predict the presence of the Nipah virus based on the reported symptoms.
The machine might output a probability, for instance, 73% (this is just an example, not a real model output).

## Requirements

- Python 3.x
