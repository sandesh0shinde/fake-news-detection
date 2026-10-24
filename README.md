# Fake News Detection Using Machine Learning

## 1. Introduction

This is my Machine Learning project for classifying news articles as FAKE or REAL based on their text.

The project uses Natural Language Processing (NLP) and Machine Learning algorithms to learn patterns from a labelled news dataset.

**Note:** The model predicts labels based on its training data. It cannot independently verify whether a news article is true or false.

## 2. Project Objectives

- To understand the basics of Natural Language Processing.
- To convert text into numerical features using TF-IDF.
- To train Machine Learning classification models.
- To evaluate and compare model performance.
- To make predictions on sample news text.

## 3. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 4. Machine Learning Models

I trained and compared two models:

1. Logistic Regression
2. Multinomial Naive Bayes

## 5. Project Workflow

1. Load the news dataset.
2. Explore the dataset and check missing values.
3. Prepare the news text and labels.
4. Split the data into training and testing sets.
5. Convert the text into numerical features using TF-IDF.
6. Train both Machine Learning models.
7. Evaluate and compare model performance.
8. Test predictions using sample news text.

## 6. Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 92.42% |
| Multinomial Naive Bayes | 87.13% |

Logistic Regression achieved the higher accuracy on the test dataset.

## 7. How to Run the Project

1. Open the notebook `fake-news-detection.ipynb` in Google Colab.
2. Run the code cells from top to bottom.
3. Allow the dataset to load.
4. Train the models and review the results.

The notebook downloads the dataset from its configured URL, so an internet connection is required.

## 8. Limitations

- The model learns patterns from the dataset and may make incorrect predictions.
- Its performance may change when it receives news from different sources.
- Accuracy alone does not show every type of prediction error.
- The model does not independently fact-check news articles.

## 9. Future Improvements

- Try additional Machine Learning models.
- Test the model on a separate dataset.
- Improve text preprocessing.
- Build a simple web application for predictions.
- Use reliable fact-checking sources to verify news claims.

## 10. Conclusion

This project helped me learn how to apply Machine Learning and Natural Language Processing to text classification. I also learned how to train models, compare their accuracy, and test predictions using Python.

## Author

Sandesh Shinde
