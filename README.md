# Sentiment Analysis on Unstructured Data in Python

This repository contains a Sentiment Analysis project implemented in Python using Selenium, Pandas, NumPy, and Scikit-learn. The project focuses on analyzing sentiments in unstructured textual data using the Multinomial Naive Bayes theorem.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Report](#report)
- [Contributing](#contributing)
- [License](#license)

## Introduction

 Sentiment Analysis is a natural language processing technique used to determine the emotional tone behind a piece of text.

 In this project, we use Python and various libraries to analyze sentiments in unstructured data, such as customer reviews or social media comments. The Multinomial Naive Bayes theorem is applied to classify text into positive, negative, or neutral sentiments.

## Installation

 1. **Clone the Repository:** Start by cloning this repository to your local machine using the following command:

	git clone https://github.com/skbadhe/Sentiments-Analysis-on-Unstructured-data.git


2. **Install Dependencies:** Install the required libraries.


3. **Web Scraping Setup:** If you want to analyze sentiments from web data, make sure to have [ChromeDriver](https://sites.google.com/chromium.org/driver/) installed and set its path in the script.

## Usage

1. **Data Collection:** If web scraping, use the `selenium` library to collect unstructured text data (reviews, comments, etc.) from websites.

2. **Data Preprocessing:** Clean and preprocess the collected data using Pandas and NumPy, including steps like tokenization, lowercasing, and removing special characters.

3. **Feature Extraction:** Convert the preprocessed text into numerical features using techniques like TF-IDF (Term Frequency-Inverse Document Frequency).

4. **Model Building:** Implement a Multinomial Naive Bayes classifier using Scikit-learn. Train the model on a labeled dataset of sentiments.

5. **Prediction and Analysis:** Use the trained model to predict sentiments for new text data. Analyze the results and calculate accuracy metrics.

## Report

 The report is uploaded in /report path of this repository which was submitted in the engineering college as a project report. This is the document from the word report, actual report was made in latex which is not uploaded here. 

## Contributing

 Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

## License

 This project is licensed under the MIT License.