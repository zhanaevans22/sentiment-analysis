# NLP Sentiment Analysis

**Author:** Zhana Evans  
**Course:** COP4023 – Programming Languages  
**University:** Florida A&M University

## Project Overview

This project uses Natural Language Processing (NLP) and a Long Short-Term Memory (LSTM) neural network to classify customer reviews as positive or negative.

## Technologies Used

- Python
- Google Colab
- Pandas and NumPy
- NLTK
- WordCloud
- Scikit-learn
- TensorFlow and Keras

## Project Features

- Data cleaning and missing value removal
- Stop-word removal
- WordCloud visualization
- Label encoding and tokenization
- LSTM neural network
- 80/20 training and testing split
- Sentiment prediction and classification report

## Model Results

| Metric | Result |
|---|---:|
| Original dataset | 3,150 reviews |
| Cleaned dataset | 3,149 reviews |
| Training samples | 2,519 |
| Testing samples | 630 |
| Model parameters | 269,442 |
| Training epochs | 5 |
| Training accuracy | 95.08% |
| Testing accuracy | 92.86% |

## How to Run

1. Download or open the Jupyter notebook in Google Colab.
2. Obtain the customer_reviewers.tsv dataset from the instructor.
3. Upload the dataset to the Colab session.
4. Run the notebook cells in order.
5. Review the model training results and classification report.

Package versions are provided in requirements.txt.

## Conclusion

The model successfully classified customer sentiment with 92.86% testing accuracy. The model performed better on positive reviews than negative reviews due to the dataset's class imbalance.
