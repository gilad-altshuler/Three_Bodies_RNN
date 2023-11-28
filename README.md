# Three_Bodies_RNN

## About
For research in the field of computational neuroscience - generating Three Bodies RNN and analyzing the new dynamics.

## Files in The Repository

|File name         | Purpose |
|----------------------|------|
|`Three Bodies Network.ipynb`|Main code section for the model and trials|
|`Models.py`|Proposed models code: <br> (1) Full Rank RNN <br> (2) Full Rank Three Bodies Network <br> (3) Low Rank RNN <br> (4) Low Rank Three Bodies Network|
|`K_Bit_Flipflop_task.py`|Data generation and draw charts methods for this task|
|`sin_task.py`|Data generation and draw charts methods for this task|
|`utils.py`|Network connectivity, fire rate, low dimension and illustrations methods|
|`models`|Directory for trained full rank models paths|
|`Low_Rank_Rnn`|Directory for trained low rank models paths|
|`Experiments.pdf`|File shows main trials and results|

## Run

All the codelines needed can be found in ECG_classification.ipynb.
To be able to run the dataset one need to:

(1) Download manually the datasets from https://www.kaggle.com/shayanfazeli/heartbeat.

(2) Uploading to your drive to the directory /content/drive/MyDrive/Deep_Learning/datasets (default in code)

(3) One can choose other directory in drive, but change the link in the code.*

*the last directory must be called "datasets"

This will allow the rest of code to use the heartbeats datasets.

## Results

- Training the model on datasets:
