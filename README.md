## AutoEncoder-and-Classifier-of-MNIST-images

> We aim to build different Neural Networks in order to achieve 2 goals:
1. AutoEncoder's implementation.
2. Classifier's implementation.

> Auto-Encoder is made up of one encoder and one decoder. User will be asked to give hyperparameters in order to build different Auto-Encoders and by observing their results he can save model which performed better.

> Classifier will be made up of the half part of previous Auto-Encoder, more specifically only 'Encoder' part, and then a fully connected layer. With same mindset user has the freedom to build several models and plot his experiment's results or save whichever model he prefers.

## Compilation & Execution

- For AutoEncoder: *python src/autoencoder.py -d data/train/train-images-idx3-ubyte*

- For Classifier: *python src/classification.py -d data/train/train-images-idx3-ubyte -dl data/train/train-labels-idx1-ubyte -t data/test/t10k-images-idx3-ubyte -tl data/test/t10k-labels-idx1-ubyte -model dropoutautoencoder.h5*

## Results
> From directory 'results_of_experiments' we are going display plots, loss vs epochs with specific hyperparameters after a series of experiments (tuning), from our best models. Note that inside this directory we saved some pretty good models for AutoEncoder, but also for Classifier.

1. Firstly for Auto-Encoder:

![alt text](https://github.com/spympr/AutoEncoder-and-Classifier-of-MNIST-images/blob/master/results_of_experiments/Results_A/Best_Model/Best_Model_With_Different_Batch_Sizes/Batch_Size_32.png)

2. Secondly for Classifier:

![alt text](https://github.com/spympr/AutoEncoder-and-Classifier-of-MNIST-images/blob/master/results_of_experiments/Results_B/Best_Model/Extra_Experiment_With_Reduced_Batch_Size_32/Epochs_40*Batch_Size_32*FC_Units_128.png)

- Correct Labels

![alt text](https://github.com/spympr/AutoEncoder-and-Classifier-of-MNIST-images/blob/master/results_of_experiments/Results_B/Best_Model/correct1.jpg)

- InCorrect Labels

![alt text](https://github.com/spympr/AutoEncoder-and-Classifier-of-MNIST-images/blob/master/results_of_experiments/Results_B/Best_Model/incorrect1.jpg)


## Contributors
1. [Alexandra Apostolopoulou](https://github.com/alexaapo)
2. [Spyros Briakos](https://github.com/spympr)
