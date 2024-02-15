# Personality Prediction using MBTI

This project aims to predict personality types using the Myers-Briggs Type Indicator (MBTI) based on textual data. The Myers-Briggs Type Indicator is a popular psychometric tool used to determine personality preferences and categorize individuals into one of sixteen personality types.

## Overview

The project involves natural language processing techniques and machine learning algorithms to analyze text data associated with MBTI types and predict the personality type of individuals based on their writing style.

## Installation

To run this project, you need to have Python installed. Additionally, you'll need the following libraries:

- NLTK
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn

You can install these libraries using pip:

```bash
pip install nltk pandas numpy matplotlib seaborn plotly scikit-learn
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/sezalk/mbti.git
```

2. Navigate to the project directory:

```bash
cd mbti
```

3. Open and run the Jupyter Notebook:

```bash
jupyter notebook mbti.ipynb
```

## Data

The dataset used in this project (`mbti_1.csv`) contains posts from various online forums along with their corresponding MBTI types. 

## Project Structure

- **mbti.ipynb**: Jupyter Notebook containing the code for preprocessing, model training, and evaluation.
- **mbti_1.csv**: CSV file containing the dataset.
- **README.md**: This file, containing project information and instructions.

## Example Output

Upon running the notebook, you'll see descriptive statistics about the dataset, including dimensions, information, and null value counts. Additionally, visualizations such as pie charts and histograms will be generated to illustrate the distribution of MBTI personality types and the lengths of all posts.


