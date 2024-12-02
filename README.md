# LLM Project - README

## Overview

This project applies machine learning and neural networks to classify text into multiple categories. It includes both traditional models (like Logistic Regression) and a fine-tuned BERT-based approach (`bert-base-german-cased`). The focus is on effective preprocessing, modeling, and evaluation.

## Features

- **Text Preprocessing**: Cleaning, balancing, and feature extraction using TF-IDF.
- **Conventional Models**: Logistic Regression with detailed evaluation metrics.
- **Neural Networks**: Fine-tuning BERT with Hugging Face’s `Trainer` API.
- **Visualization**: Insights into data distribution and model results.


## Workflow

1. **Data Preparation**: Clean and preprocess text data.
2. **Model Training**: 
   - Run logistic regression with TF-IDF features.
   - Fine-tune and evaluate BERT for better performance.
3. **Evaluation**: Check accuracy, precision, recall, and F1 scores.

## Results

- Logistic Regression: ~37% accuracy.
- Fine-tuned BERT: ~45% accuracy with improved class-wise performance.

## Future Work

- Experiment with different models and parameters.
- Improve generalization with more data or ensemble methods.

## License

MIT License. Contributions are welcome!
