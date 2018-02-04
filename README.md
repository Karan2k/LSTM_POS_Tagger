# LSTM_POS_Tagger
A simple POS Tagger made using a Bidirectional LSTM using keras trained on the Brown Corpus

Paper used as reference - [Part-of-Speech Tagging with Bidirectional Long Short-Term Memory Recurrent Neural Network](https://arxiv.org/pdf/1510.06168.pdf)

See [DetailedDescription.pdf]((https://github.com/aneesh-joshi/LSTM_POS_Tagger/blob/master/DetailedDescription.pdf)) for a detailed description of the whole project.


**Video Explanation:**
A video explaining the whole project can be found [here](https://drive.google.com/open?id=0B5-t3yDeHRzKVEZ4VUMwSWtwbDA)

**TL;DR:**
The code does the following:

1. Extracts POS tagging training data from the Brown corpus (`extract_data.py`)
2. Converts a text file with the Glove Vectors into a pickle file (`make_glove_pickle.py`)
3. Trains a Bidirectional LSTM using the vectors and data. (`make_model.py`)
4. Allows pos tag prediction on new sentences fed in through `model_evaluation.py`

Uses keras and tensorflow backend

Glove file not included
