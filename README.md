# elmo_experiments
This repository is experiments of ELMo that deep contextualized word representation by Keras.

<img src="https://github.com/kamujun/elmo_experiments/blob/master/docs/images/ELMo.png" width="600px">


ELMo is contextualized word representations using character-based word representations and bidirectional LSTMs.
TensorFlow hub provides ELMo module that was trained on the 1 Billion Word Benchmark.

# Getting start
```
$ pip install -r requirements.txt
```
NOTE:If use tensorflow with cpu support, need installing that by your self.

# Experiments
## Text classification on IMDB
This experiments is text classification with ELMo, LSTM and word embedding on IMDB dataset.
Evaluate ELMo text classification and compare that to LSTM model.

https://github.com/kamujun/elmo_experiments/blob/master/elmo_experiment/notebooks/elmo_text_classification_on_imdb.ipynb

## Result
ELMo's 1st epoch get best score.

<img src="https://github.com/kamujun/elmo_experiments/blob/master/docs/images/elmo_classification_accuracy.png" width="300px">
