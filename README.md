# Numerai_Deepnet

This repository contains code to load and train a deepnet on the numerai dataset. This is a very basic version that can be easily tuned to produce origional results. The deepnet architecture is loosely based off of fractalnet.

The current version contains only 27k params and achieves competitive results in only 30mins of training on a cheap laptop CPU.

![numerai accuracy](https://github.com/Seanai-Higgins/Numerai_Deepnet/blob/master/Images/numerai_accuracy.png?raw=true)
![numerai loss](https://github.com/Seanai-Higgins/Numerai_Deepnet/blob/master/Images/numerai_loss.png?raw=true)


### MNIST testing:

Given how easy it is to modify keras deepnets, I tried my luck on the MNIST dataset. The current state of the art is [99.79% accuracy](https://rodrigob.github.io/are_we_there_yet/build/classification_datasets_results.html) and using this modified numerai deepnet, we achieve accuracies of 99.51% with a mere 30 minutes of laptop CPU training and 130k params. 

![MNIST accuracy](https://github.com/Seanai-Higgins/Numerai_Deepnet/blob/master/Images/accuracy.png?raw=true)
![MNIST logloss](https://github.com/Seanai-Higgins/Numerai_Deepnet/blob/master/Images/loss.png?raw=true)
