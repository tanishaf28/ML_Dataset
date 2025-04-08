
# Sleep Disorder Detection from PPG Signals

This project focuses on detecting sleep disorders using PPG signals. The goal is to identify potential sleep disorders, such as sleep apnea, by analyzing heart rate and other related metrics using photoplethysmography (PPG) signals. The project leverages machine learning techniques to preprocess, analyze, and classify PPG data.

## Project Overview

The pipeline includes the following steps:

1. **Data Collection**: PPG data is collected from wearables.
2. **Data Preprocessing**: The data is cleaned and processed, including feature extraction and signal conditioning.
3. **Model Training**: A Random Forest model is trained to detect sleep disorders.
4. **Evaluation**: The model's performance is evaluated with metrics such as accuracy, precision, recall, and F1-score.

### Features

- **Real-time detection**: Using PPG signals to identify sleep patterns and abnormalities.
- **Data preprocessing**: Handling artifacts and noise in raw PPG signals.
- **Machine learning models**: Random Forest and LSTM models for classification.
- **Performance evaluation**: Precision, recall, and F1-score metrics to assess the model.


## Project Links

- [Google Colab Notebook](https://colab.research.google.com/drive/12VisBncJYrLw0FXjMNdxE24D_nHcGdG1?usp=sharing) - Test the model with real data.
- [GitHub Repository](https://github.com/tanishaf28/ML_Dataset) - Access the project code and dataset.
- [Tableau Dashboard](https://public.tableau.com/app/profile/tanisha.fonseca/viz/Feature-Analysis/Dashboard1) - Explore the feature analysis and results in Tableau.

## Usage

- Load your own PPG dataset for testing.
- Train the model on the dataset using the Jupyter notebook provided in the `Notebooks` folder.
- Evaluate the model’s performance and visualize results using the built-in metrics.
