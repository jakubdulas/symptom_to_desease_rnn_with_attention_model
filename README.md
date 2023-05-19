# Symptom to Disease RNN with Attention Model

This repository contains the code and resources for training and using a Recurrent Neural Network (RNN) model with attention mechanism to predict diseases based on symptoms.

## Overview

The Symptom to Disease RNN with Attention Model is designed to analyze a given set of symptoms and predict the most probable disease that could be associated with those symptoms. It utilizes an RNN architecture with attention mechanism to capture the dependencies and relationships between symptoms and diseases.

The model is trained on a dataset that consists of symptom-disease pairs, where each symptom is associated with a disease. During training, the RNN learns to recognize patterns and make accurate predictions based on the given symptoms.

## Model Architecture

The RNN model with attention mechanism consists of the following components:

1. **Embedding Layer**: Converts input symptoms into dense vectors that can be processed by the RNN.
2. **Recurrent Layer**: Utilizes Long Short-Term Memory (LSTM) cells to capture temporal dependencies between symptoms.
3. **Attention Mechanism**: Attends to relevant symptoms while predicting diseases by assigning weights to different parts of the input sequence.
4. **Fully Connected Layer**: Maps the hidden states from the recurrent layer to the output classes (diseases).
5. **Softmax Activation**: Produces a probability distribution over the diseases, indicating the likelihood of each disease given the input symptoms.

## Usage

### Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy

### Installation

1. Clone the repository:

```bash
git clone https://github.com/jakubdulas/symptom_to_desease_rnn_with_attention_model.git
cd symptom_to_desease_rnn_with_attention_model
```

## License

This project is licensed under the [MIT License](LICENSE).
