# Audio-Classification-Using-Rnn
### Audio Classification with LSTM on UrbanSound8K Dataset

This project involves building a machine learning model to classify urban sound events using the UrbanSound8K dataset. The workflow includes:

- **Data Processing**: Utilized `librosa` for audio feature extraction, focusing on MFCCs for representing sound signals.
- **Model Development**: Implemented a deep learning model using LSTM layers in TensorFlow/Keras to capture temporal dependencies in audio data.
- **Evaluation**: Split the dataset into training and test sets, with performance metrics calculated to assess the model's accuracy.
## Dataset
The dataset used for this project can be found [here](https://www.kaggle.com/datasets/chrisfilo/urbansound8k).

## How to Run
1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebook to preprocess data, train the model, and evaluate its performance.

Libraries: `librosa`, `pandas`, `numpy`, `scikit-learn`, `tensorflow/keras`
