

# Movie Genre Classification

This project aims to predict the genre of a movie based on its plot summary or other textual information using machine learning techniques. The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb).

## Dataset

The dataset contains movie plot summaries along with their corresponding genres. Each row in the dataset represents a movie, and the columns include:

- **Title**: The title of the movie.
- **Plot**: The plot summary of the movie.
- **Genre**: The genre(s) of the movie.

You can download the dataset from [here](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb).

## Techniques Used

- **Text Preprocessing**: The plot summaries are preprocessed to remove noise, tokenize the text, and perform other necessary text cleaning steps.
- **Feature Extraction**: Techniques like TF-IDF (Term Frequency-Inverse Document Frequency) or word embeddings are used to convert the textual data into numerical features.
- **Machine Learning Models**: Several classifiers such as Naive Bayes, Logistic Regression, and Support Vector Machines (SVM) are employed to train the model on the extracted features.
- **Evaluation**: The performance of each model is evaluated using appropriate evaluation metrics such as accuracy, precision, recall, and F1-score.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/movie-genre-classification.git
    ```

2. Navigate to the project directory:

    ```bash
    cd movie-genre-classification
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the main script to train and evaluate the model:

    ```bash
    python main.py
    ```

## Results


              precision    recall  f1-score   support

           0       0.40      0.01      0.02       256
           1       0.60      0.02      0.05       127
           2       0.00      0.00      0.00       146
           3       0.00      0.00      0.00        91
           4       0.00      0.00      0.00        42
           5       0.35      0.07      0.12      1488
           6       0.00      0.00      0.00        96
           7       0.47      0.22      0.30      2666
           8       0.42      0.10      0.15      2777
           9       0.00      0.00      0.00       151
          10       0.00      0.00      0.00        70
          11       0.71      0.10      0.17        51
          12       0.00      0.00      0.00        44
          13       0.44      0.11      0.18       480
          14       0.39      0.10      0.16       131
          15       0.00      0.00      0.00        49
          16       0.00      0.00      0.00        73
          17       0.00      0.00      0.00        44
          18       0.27      0.02      0.03       173
          19       0.00      0.00      0.00       158
          20       0.50      0.02      0.03       118
          21       0.40      0.04      0.07       961
          22       0.50      0.01      0.02        97
          23       1.00      0.01      0.02        86
          24       0.12      0.00      0.01       321
          25       0.00      0.00      0.00        35
          26       0.49      0.13      0.21       218
          27       0.50      0.89      0.64     10734

    accuracy                           0.49     21683
   macro avg       0.27      0.07      0.08     21683
weighted avg       0.44      0.49      0.39     21683

Accuracy:  0.48969238573998064
r2_Score:  -0.798120066550621

## Conclusion

In this project, we explored the task of movie genre classification using machine learning techniques. The Support Vector Machine (SVM) classifier achieved the highest accuracy among the models evaluated. Further improvements could be made by experimenting with different text preprocessing techniques, feature extraction methods, and model architectures.

