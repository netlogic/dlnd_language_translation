Hi!  Thank you taking the time to review my project 4 language_translation

I look forward to any help or comments.

All files can be found at the following github address:

    https://github.com/netlogic/dlnd_language_translation/commits/master

The commit history as I built the neural network can be found at:

    https://github.com/netlogic/dlnd_language_translation/commits/master

This project relied on the classwork of the Sequence To Sequence
project (Lesson 10 of the RNN section) which alphabetized 
a sequence of random letter fed into the system.

My list of hyper params and their corresponding results can be found below.
Increasing the encoding and decoding embedding size
increased accuracy, validation, and decreased loss.

The section on cloud computing in the course is great.
I continue to use my AWS gpu and training time is 
~ 10-15 minutes with the different hyperparams.

Interestingly increasing layers increased my loss slighty and 
did not increase my training Accuracy but did finally
lead to a correct translation for yellow to juane.
The other hyper params gave me red or white.
So I will stick with the 3 layer network.

All work shown in the html file.

Thank you again for your help.



Hyper Params:
 Number of Epochs
epochs = 10
-# Batch Size
batch_size = 100
-# RNN Size
rnn_size = 256
-# Number of Layers
num_layers = 2
-# Embedding Size
encoding_embedding_size = 64
decoding_embedding_size = 64
-# Learning Rate
learning_rate = .01
-# Dropout Keep Probability
keep_probability = 1
display_step = 5

Epoch   9 Batch 1375/1378 - Train Accuracy: 0.9786, Validation Accuracy: 0.9486, Loss: 0.0377


- # Number of Epochs
epochs = 10
- # Batch Size
batch_size = 100
- # RNN Size
rnn_size = 256
- # Number of Layers
- num_layers = 2
- # Embedding Size
encoding_embedding_size = 64
decoding_embedding_size = 64
- # Learning Rate
learning_rate = .01
- # Dropout Keep Probability
keep_probability = .75
display_step = 5
Epoch   9 Batch 1375/1378 - Train Accuracy: 0.9367, Validation Accuracy: 0.8805, Loss: 0.0890
Model Trained and Saved

-# Number of Epochs
epochs = 10
-# Batch Size
batch_size = 500
-# RNN Size
rnn_size = 256
-# Number of Layers
num_layers = 2
-# Embedding Size
encoding_embedding_size = 64
decoding_embedding_size = 128
-# Learning Rate
learning_rate = .01
-# Dropout Keep Probability
keep_probability = .75
display_step = 250

Epoch   9 Batch  250/275 - Train Accuracy: 0.9651, Validation Accuracy: 0.9743, Loss: 0.0185
Model Trained and Saved


- # Number of Epochs
epochs = 10
-# Batch Size
batch_size = 500
-# RNN Size
rnn_size = 256
-# Number of Layers
num_layers = 2
-# Embedding Size
encoding_embedding_size = 128
decoding_embedding_size = 128
-# Learning Rate
learning_rate = .01
-# Dropout Keep Probability
keep_probability = .75
display_step = 250

Epoch   9 Batch  250/275 - Train Accuracy: 0.9729, Validation Accuracy: 0.9763, Loss: 0.0155
Model Trained and Saved

-# Number of Epochs
epochs = 10
-# Batch Size
batch_size = 500
-# RNN Size
rnn_size = 256
-# Number of Layers
num_layers = 3
-# Embedding Size
encoding_embedding_size = 128
decoding_embedding_size = 128
-# Learning Rate
learning_rate = .01
-# Dropout Keep Probability
keep_probability = .75
display_step = 125

Epoch   9 Batch  250/275 - Train Accuracy: 0.9675, Validation Accuracy: 0.9730, Loss: 0.0255
Model Trained and Saved




