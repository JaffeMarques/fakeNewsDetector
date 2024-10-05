# Fake News Detector

## Project Overview
This project implements a machine learning model to detect fake news articles using natural language processing techniques. It's implemented as a Jupyter Notebook and utilizes various Python libraries for data processing, model training, and visualization.

## Features
- Data collection from a GitHub repository
- Text preprocessing and feature extraction
- Machine learning model training (Logistic Regression)
- Model evaluation
- Visualization of word frequencies for fake and true news using word clouds

## Dependencies
The project requires the following Python libraries:
- gitpython
- Unidecode
- nltk
- pandas
- numpy
- scikit-learn
- matplotlib
- Pillow
- wordcloud

You can install these dependencies using pip:

```
!pip install gitpython Unidecode nltk pandas numpy scikit-learn matplotlib Pillow wordcloud
```

## Data Source
The project uses the Fake.br-Corpus dataset, which is cloned from the following GitHub repository:
https://github.com/roneysco/Fake.br-Corpus

## Workflow
1. Data Collection: The script clones the Fake.br-Corpus repository and reads the fake and true news articles.
2. Data Preprocessing: The text data is cleaned, normalized, and preprocessed.
3. Feature Extraction: TF-IDF vectorization is used to convert text data into numerical features.
4. Model Training: A Logistic Regression model is trained on the preprocessed data.
5. Model Evaluation: The model's accuracy is calculated and printed.
6. Visualization: Word clouds are generated to visualize the most frequent words in fake and true news articles.

## Results
The model's accuracy is printed at the end of the notebook. Two word cloud visualizations are generated:
1. A green "thumbs up" shaped word cloud for true news articles.
2. A red "thumbs down" shaped word cloud for fake news articles.

## Usage
To use this project:
1. Ensure all dependencies are installed.
2. Run the Jupyter Notebook in an environment with access to the required libraries.
3. The notebook will automatically download the necessary NLTK data and clone the Fake.br-Corpus repository.
4. Run all cells to see the results and visualizations.

## Note
This project is for educational purposes and demonstrates basic techniques in natural language processing and machine learning. The accuracy of fake news detection may vary and should not be considered definitive without further validation.
