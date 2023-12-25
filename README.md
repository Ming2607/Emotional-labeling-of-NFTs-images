# NLP Analysis of NFT Image Emotion Annotations
This project involves NLP analysis using Python and NLTK library to process data related to NFT image emotion annotations of 240 subjects.  It performs various tasks including part-of-speech classification, and de-duplication.

# Project Overview
The code is structured into several sections:
## 1. The frequency of each person's emotional choices
Selects columns related to images from the data and aggregates the frequency of each emotion per person, creating a dictionary for subsequent use.

Generates a CSV file 1_expert.csv that records the frequency of each emotion choice for every individual.


## 2. Count the number of choices for each emotion by item
Reads data files and extracts specific columns to tally the count of each emotion selection.

Outputs the results to 2_expert.csv, documenting the count of each emotion choice per project.


## 3. The text of emotion interpretation is divided into words and word frequency is extracted
Chooses columns containing 'explain', compiles the content into a string list, tokenizes, and removes stopwords and punctuation.

Computes word frequency to produce a frequency distribution plot.


## 4. Output word frequency and part of speech
Computes word frequency based on tokenization results, recording the word type for each word, generating a CSV file 4_expert.csv.


## 5. Eight key words affective tendency
Imports specific columns from the original data, processes column names, and analyzes the appearance of each keyword in each image/person, outputting the analysis results into multiple files.


## 6. Judgment of positive/negative emotions
Reads data and encodes emotions (positive as 1, negative as -1, and others as 0), saving the results in 6_expert.csv.


# Usage Instructions
## Requirements

Ensure Python, Pandas, NLTK, Seaborn, and Numpy are installed.

## Running the Code

Clone the repository and execute each code section sequentially.
Adjust file paths as needed for data access.

## Data Sources

Utilizes SPSS data files; ensure access to these files for proper code execution.

