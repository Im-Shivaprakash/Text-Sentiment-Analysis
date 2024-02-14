# Text Sentiment Analysis using LSTM

This project focuses on performing text sentiment analysis using Long Short-Term Memory (LSTM) networks. The objective is to classify the sentiment (positive or negative) behind textual data. We utilize various Natural Language Processing (NLP) techniques for data preprocessing and LSTM layers to build the text classifier.

## Dataset

The dataset used in this project contains over 14,000 tweet samples classified into three categories: positive, negative, and neutral sentiments. For sentiment analysis, we focus on classifying tweets into positive or negative categories.

Dataset Link: [Tweets Dataset](https://drive.google.com/file/d/13B2iHgXgOF_64klnwte9Ll9Ri_4D9EGE/view?usp=drive_link)

## Project Overview

- **Preprocessing**: We preprocess the textual data using NLP techniques to clean and tokenize the text.
- **Model Architecture**: The model architecture consists of an embedding layer, LSTM layer, and a Dense layer for classification.
- **LSTM (Long Short-Term Memory)**: LSTM networks are employed for handling sequential data and capturing long-term dependencies.
- **Dropout Mechanism**: Dropout layers are introduced to prevent overfitting by randomly dropping out nodes during training.
- **Training**: The model is trained on the preprocessed tweet data to learn the sentiment patterns.
- **Evaluation**: We evaluate the model's performance using accuracy metrics and visualize training/validation loss and accuracy.

## Usage

1. **Data Loading**: Load the tweets dataset containing text and sentiment labels (positive/negative/neutral).
2. **Data Preprocessing**: Perform NLP preprocessing techniques such as tokenization and padding.
3. **Model Training**: Train the LSTM model on the preprocessed data to learn sentiment patterns.
4. **Evaluation**: Evaluate the model's performance using accuracy metrics and visualize training/validation loss and accuracy.
5. **Prediction**: Utilize the trained model to predict the sentiment of new text data.

## File Structure

- `sentiment_analysis.py`: Python script containing the project code for data preprocessing, model building, training, and evaluation.
- `Tweets.csv`: Dataset file containing tweet text and sentiment labels.

## Dependencies

- Pandas
- Matplotlib
- TensorFlow
- Keras

## Contributions

Contributions to this project are welcome! Whether it's bug fixes, enhancements, or new features, feel free to open issues or submit pull requests to improve the functionality and performance of this sentiment analysis project.

## License

This project is licensed under the MIT License. Refer to the [LICENSE](LICENSE) file for detailed terms and conditions.
