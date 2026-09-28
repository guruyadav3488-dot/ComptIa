# Deep Learning Projects

A collection of hands-on deep learning projects built with TensorFlow/Keras, covering
image classification (CNNs), sequence modelling (RNNs) and time-series forecasting (LSTMs).

## Projects

| Project | What I built | Architecture |
|---|---|---|
| [Alzheimer MRI Classifier](alzheimer-mri-classifier) | Classifies brain MRI scans into 4 stages of Alzheimer's | CNN (3 conv blocks) |
| [Digits Classifier](digits-classifier) | Recognises handwritten digits 0-9 (~94% test accuracy) | CNN (2 conv layers) |
| [RNN Text Prediction](rnn-text-prediction) | Predicts the next character and next word from text | SimpleRNN |
| [LSTM Architectures](lstm-concepts) | Reference of 8 LSTM designs: stacked, bidirectional, multivariate, seq2seq | LSTM |
| [NYC Temperature Forecast](lstm-temperature-forecast) | Forecasts daily temperature, compares 4 LSTM variants with MAE/RMSE/R2 | LSTM |

## Skills Demonstrated

- Image classification with CNNs and `ImageDataGenerator`
- Text modelling at character and word level, with embeddings
- Time-series preprocessing: scaling, sliding windows, train/test split
- Model comparison and evaluation (MAE, RMSE, R2)
- Saving and reloading trained models for inference

## Setup

```bash
git clone https://github.com/<your-username>/deep-learning-projects.git
cd deep-learning-projects
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## Notes

- Datasets are not included. Each project README says what to download and where to put it.
- Trained model files (`.h5`, `.keras`) are git-ignored.
