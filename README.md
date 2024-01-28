# Pretrained-model-Comparison-using-Topsis
## Project Overview

Welcome to the Text Sentence Similarity Model Comparison project! This project aims to assist users in selecting the most suitable text Sentence Similarity model for their needs by comparing various pre-trained models using the Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) method. By evaluating essential metrics such as cosine similarity, Euclidean distance, and Manhattan distance.
## Key Features:

1. **Metrics Considered:**
   - Evaluation is based on a comprehensive set of metrics including Cosine similarity, Euclidean distance,and Manhattan distance, offering a holistic view of model performance in Similarity tasks.
2. **Methodology - TOPSIS:**
   - The TOPSIS method is utilized for comparison, considering both similarity to the ideal solution and dissimilarity to the negative ideal solution, ensuring a robust ranking of  models.

3. **Models Evaluated:**
   - Models such as BERT, RoBERTa ,XLNet, USE, ALBERT, and DistilBERT are evaluated, reflecting real-world pre-trained models commonly used in Sentence Similarity tasks.

## Project Structure:

- **`data.csv`**: Contains evaluation metrics for each model.
- **`result.csv`**: Provides ranked results in a tabular format for easy analysis.

## Results and Analysis:
1. **Ranked Table:**
- Refer to conversational_table_result.csv for detailed ranked results.

| **Model**   | **Cosine Similarity**    | **Euclidean Distance** | **Manhattan Distance**  |
|-------------|--------------------------|------------------------|-------------------------|
| BERT        | 0.92                     | 1.5                    | 6.2                     |
| RoBERTa     | 0.94                     | 1.3                    | 5.8                     |
| XLNet       | 0.91                     | 1.6                    | 6.5                     |
| USE         | 0.93                     | 1.4                    | 6.0                     |
| ALBERT      | 0.90                     | 1.7                    | 6.8                     |
| DistilBERT  | 0.89                     | 1.8                    | 7.0                     |




## Analysis:
**Model Performance:**
RoBERTa has the highest cosine similarity, suggesting it captures semantic similarity well.
ALBERT and DistilBERT have lower Euclidean and Manhattan distances, indicating closer embeddings and higher similarity.
