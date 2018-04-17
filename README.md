# Machine Translation

## Introduction
Build a deep neural network that functions as part of an end-to-end machine translation pipeline. The pipeline accepts English text as input and returns the French translation. There are three main steps:

* Preprocess - Convert text to sequence of integers.
* Models - Create models which accept a sequence of integers as input and return a probability distribution over possible translations.
* Prediction - Run the best model on English text.

## Models 
I have experimented with five different neural network architectures. 

* Model 1 is a simple RNN
* Model 2 is an RNN with Embedding
* Model 3 is a Bidirectional RNN
* Model 4 is an Encoder-Decoder RNN
* Model 5 incorporates embedding, encoder-decoder and bidirectional RNN. It is the best performer, achieving an accuracy of 99%.

## Code

* `machine_translation.ipynb` - The main code for this project, which contains the three steps mentioned above.
* `helper.py` - Contains a helper function to load data.
* `project_tests.py` - Tests the functions implemented in `machine_translation.ipynb`.

## Setup

* Python 3
* NumPy
* TensorFlow 1.x
* Keras 2.x

## Run
To run any notebook, use:

`jupyter notebook machine_translation.ipynb`

To run any script file, use:

`python <script.py>`

