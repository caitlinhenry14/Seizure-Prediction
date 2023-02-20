# Seizure Prediction
CNN and LSTM architecture to predict seizures based on [EEG data](https://www.epilepsyecosystem.org). It won't cure my seizure condition, but it's... nice... I guess. The project can be broken down into two parts:

Preprocessing (MATLAB)
- Denoises EEG Data

CNN + LSTM (Python)
- Model is trained using preprocessed data
- Generator.py loads data into memory in batches as opposed to all at once

## Project Execution
To run the project, first download the repository and run `pip3 install -r requirements.txt`. 

Train the model by running `python3 seizure_prediction.py -- mode train`. 

Test the model by running `python3 seizure_prediction.py -- mode test`.
