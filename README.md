Part 1 - FFNN for NER Tagging
Description:
I've developed a Feedforward Neural Network (FFNN) model for Named Entity Recognition (NER) tagging. Its task is to predict NER tags (e.g., PERSON, ORGANIZATION, LOCATION) for each word in a given sentence.

Implementation:
Our FFNN architecture consists of a single hidden layer.
The model is trained using the provided training dataset and evaluated on the validation dataset.
Hyperparameters:
- Hidden Layer Dimension: 256
- Activation Function: ReLU
- Batch Size: 512
- Number of Epochs: 15
- Learning Rate: 0.001
- L2 Regularization: 1e-05

Results:
On the validation set, the model achieves an accuracy of approximately 96%.

Part 2 - LSTM for NER Tagging
Description:
For this task, I've implemented a Long Short-Term Memory (LSTM) model for Named Entity Recognition (NER) tagging. Like the FFNN, it predicts NER tags for each word in a given sentence.

Implementation:
Our LSTM architecture is bidirectional.
The model is trained using the provided training dataset and evaluated on the validation dataset.
Hyperparameters:
- Embedding Dimension: 64
- Hidden Dimension: 128
- Batch Size: 512
- Number of Epochs: 15
- Learning Rate: 0.005
- L2 Regularization: 1e-06

Results:
The LSTM model achieves an accuracy of approximately 97% on the validation set.

Conclusion:
Both the FFNN and LSTM models demonstrate promising results for NER tagging. The LSTM model slightly outperforms the FFNN model, which is expected due to its ability to capture long-range dependencies in the input sequence. These models could be further enhanced through hyperparameter tuning and more complex architectures.
