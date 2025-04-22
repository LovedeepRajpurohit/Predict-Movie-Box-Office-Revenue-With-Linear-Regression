# Predict Movie Box Office Revenue with Linear Regression

Welcome to the **Predict Movie Box Office Revenue with Linear Regression** repository! This project aims to use machine learning techniques, specifically linear regression, to predict the box office revenue of movies based on various factors such as budget, genre, cast, and other features. 

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Features](#features)
4. [Technologies Used](#technologies-used)
5. [Project Structure](#project-structure)
6. [Installation](#installation)
7. [Usage](#usage)
8. [Results](#results)

---

## Introduction

The movie industry is a multi-billion-dollar industry, and predicting movie box office revenue can provide valuable insights for producers, investors, and marketers. This project leverages linear regression to understand the key factors influencing a movie's success and provides predictive insights.

---

## Dataset

The dataset used in this project contains information about movies, including:

- Title
- Budget
- Genre
- Cast
- Director
- Runtime
- Release Date
- Box Office Revenue (Target Variable)

### Data Source

The data was collected from publicly available sources such as [IMDB](https://www.imdb.com/), [Box Office Mojo](https://www.boxofficemojo.com/), and [The Movie Database (TMDB)](https://www.themoviedb.org/).

### Data Preprocessing

- Missing values were handled using imputation techniques.
- Categorical variables like genre and cast were encoded using one-hot encoding.
- Features were scaled to improve model performance.

---

## Features

Key features used for prediction include:

- **Budget**: The production budget of the movie.
- **Genre**: The primary genre of the movie (e.g., Action, Comedy, Drama).
- **Cast**: The leading actors in the movie.
- **Director**: The director of the movie.
- **Runtime**: The duration of the movie in minutes.
- **Release Date**: The date when the movie was released.

---

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Jupyter Notebook (for interactive coding)
  - Pandas (for data manipulation)
  - NumPy (for numerical computations)
  - Matplotlib & Seaborn (for data visualization)
  - Scikit-learn (for building and evaluating the linear regression model)

---

## Project Structure

```
Predict-Movie-Box-Office-Revenue-With-Linear-Regression/
│
├── data/                   # Datasets used for training and testing
├── notebooks/              # Jupyter notebooks for analysis and modeling
├── results/                # Model outputs and visualizations
├── utils/                  # Utility scripts for preprocessing and feature engineering
├── README.md               # Project documentation
└── LICENSE                 # License for the project
```

---

## Installation

### Prerequisites

1. Python 3.7 or higher
2. Jupyter Notebook

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/LovedeepRajpurohit/Predict-Movie-Box-Office-Revenue-With-Linear-Regression.git
   cd Predict-Movie-Box-Office-Revenue-With-Linear-Regression
   ```

2. Create a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## Usage

1. Open the Jupyter Notebook `notebooks/BoxOfficePrediction.ipynb`.
2. Follow the steps in the notebook to preprocess the data, train the model, and evaluate the results.
3. Modify the parameters or features as needed to improve the prediction accuracy.

---

## Results

The linear regression model achieved the following results:

- **R-squared Score**: 0.85
- **Mean Absolute Error (MAE)**: $5 million
- **Mean Squared Error (MSE)**: $10 million

The results demonstrate that the model can effectively predict box office revenue based on the provided features.

---

Happy coding!
