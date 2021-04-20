# MIDAS-MNIST


Abstract:

    This repository contains the CNN model capable of recognising hand-written digits from the MNIST Dataset.


Environment Requirements:

    Python 3.0
    Google Collab
    GPU support
    Keras-backend
    numpy
    split_folders

Dataset Links:

  Part 1:
  
    (trainPart1.zip): https://www.dropbox.com/s/pan6mutc5xj5kj0/trainPart1.zip
  Part 2:
  
    MNIST.zip: provided in this repository
    
  Part 3:
  
    mnistTask3.zip: https://www.dropbox.com/s/otc12z2w7f7xm8z/mnistTask3.zip

Observations:

TRAINING DATASET:

        A final accuracy of ~98.30% is found in part 1, ~92.75% in part 2 and ~90% in part 3.
        
TESTING DATASET:       
        
        Part 1: '4' was predicted as 'K' (Sample021) with a probability of 1.0
        Part 2: '7' was predicted as '7' (Sample008) with a probability of 1.0
        Part 3: '6' was predicted as '5' with a probability of 1.0
        
ISSUES:

    The model always gives a prediction probability of 1.0 on the testing data for most of the cases.
    
    
Author:

    Shirshakk Purkayastha
