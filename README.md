# IMDb Score Prediction using Linear Regression

This project aims to predict IMDb scores for movies available on the Films platform using a linear regression model. By following the instructions below, you can run the code and explore the project.

## Table of Contents

- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Running the Code](#running-the-code)
- [Project Structure](#project-structure)
- [License](#license)

## Dataset

The dataset used for this project is 'NetflixOriginals.csv.' This dataset contains information about Netflix original movies and is provided directly in the project directory.

### Description

- **File Name**: NetflixOriginals.csv
- **Description**: This dataset includes details about Netflix original films, such as genre, premiere date, runtime, language, and IMDb scores. It serves as the foundation for our IMDb score prediction project.

## Dependencies

Before running the code, you need to have the following dependencies installed:

- Python (version 3.6 or higher)
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

You can install these dependencies using pip by running:

```bash
pip install pandas numpy matplotlib scikit-learn

## Running the Code

Follow these steps to run the IMDb score prediction code:

* Clone or download this GitHub repository to your local machine.

* Ensure you have the dataset file 'NetflixOriginals.csv' in the project directory.

* Open a terminal or command prompt and navigate to the project directory.

* Run the Python script 'imdb_score_prediction.py' using the following command:
bash
pip install pandas numpy matplotlib scikit-learn

"python imdb_score_prediction.ipynb"

The script will perform data preprocessing, train a linear regression model, and evaluate it. It will display RMSE (Root Mean Square Error) and R-squared (R2) score, as well as a scatter plot showing actual vs. predicted IMDb scores.
Project Structure

The project directory contains the following files:

imdb_score_prediction.ipynb: The main Python script for IMDb score prediction.
NetflixOriginals.csv: The dataset file.
