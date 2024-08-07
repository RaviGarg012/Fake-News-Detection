# Fake News Detection

This project is focused on building a machine learning model to detect fake news articles. The goal is to classify news articles as either "True" or "Fake" using various machine learning techniques.

## Dataset

The dataset used in this project consists of two CSV files: `True.csv` and `Fake.csv`. Each file contains articles labeled as "True" or "Fake", respectively.

## Project Structure

- **Data Loading and Preprocessing**: The data is loaded using pandas, and initial exploration is performed to understand the dataset.
- **Feature Engineering**: Techniques are applied to extract relevant features from the text data.
- **Model Training**: Various machine learning models are trained and evaluated to find the best-performing model.
- **Evaluation**: The performance of the models is evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Installation

To run this project, you'll need to have Python installed along with the following libraries:

- pandas
- numpy
- scikit-learn

You can install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn

