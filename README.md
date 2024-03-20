# Next Word Predictor using LSTM

This repository contains code for a Next Word Predictor implemented using TensorFlow and Long Short-Term Memory (LSTM) networks. The project aims to forecast the next word in a sequence of text, showcasing expertise in deep learning and natural language processing (NLP).

## Dataset
The dataset used for training the model consists of short jokes. Due to the large size of the original dataset, a subset of 1000 rows was used for model training to expedite the process while preserving language patterns.

## Model Architecture
The model architecture includes an Embedding layer, LSTM layer, and Dense layer with a softmax activation function. The model was trained over 20 epochs using the Adam optimizer and categorical cross-entropy loss function.

## Results
The trained model demonstrates significant accuracy improvements in predicting the next word in a sequence of text. Sample predictions are provided in the `sample_predictions.txt` file.

## Future Work
Future enhancements may include experimenting with different model architectures, exploring larger datasets, and optimizing hyperparameters for improved performance.
