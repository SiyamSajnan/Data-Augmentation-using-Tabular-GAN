# Data Augmentation for Auto-MPG Prediction with Tabular GAN

## Project Description
This project employs a Generative Adversarial Network (GAN) specifically adapted for tabular data, known as Tabular GAN, to augment the Auto-MPG dataset. By synthesizing additional samples, the project aims to enhance the diversity and size of the dataset, improving the robustness and performance of a downstream Artificial Neural Network (ANN) model for predicting vehicle fuel efficiency (MPG).

## Models Employed
- **Tabular GAN**: A GAN architecture adapted for generating realistic synthetic tabular data.
- **Artificial Neural Network (ANN)**: A deep learning model for MPG prediction, trained on the augmented dataset.

## Features
- **Data Augmentation with Tabular GAN**: The Tabular GAN model was used to generate synthetic data that mimics the distribution and characteristics of the original dataset, addressing class imbalance and boosting model performance.
- **Comprehensive Data Preprocessing**: Preparation steps included normalizing features, handling missing values, and balancing the dataset before feeding it to Tabular GAN.
- **Enhanced Model Training**: The augmented dataset allowed for more robust ANN training, improving the predictive accuracy for MPG.
- **Model Evaluation**: Root Mean Squared Error (RMSE) was used as the evaluation metric to assess the predictive performance of the ANN.

## Usage
Run the Tabular GAN notebook to generate synthetic samples, which can be appended to the original dataset. Train the ANN model using this augmented dataset to see improved prediction accuracy.

## Detailed Results
After training on the augmented dataset, the ANN model achieved a Root Mean Squared Error (RMSE) of **2.98**. This improvement indicates the effectiveness of data augmentation in enhancing model performance for MPG predictions.

## Contributing
Feel free to fork this repository and submit pull requests with improvements or additional features.
