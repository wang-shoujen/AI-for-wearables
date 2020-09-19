This project consisted of three parts

1. Speech to text
2. Dialog act classification
3. Generate output

The [speech_recognition](https://pypi.org/project/SpeechRecognition/) library is used for speech to text and needs to be installed prior to use

The probabilistic dialog act classifier developed by [this project](https://github.com/NathanDuran/Probabilistic-RNN-DA-Classifier) is used to predict the dialog act
This requires the tensorflow library

The [embedding file](/embeddings/word2vec_swda_300dim.txt) was split because file size is too big for GitHub browser.
Remember to unzip it before using.

The classifier may require more work to improve accuracy.

The dialog_act_table.csv determine if a dialog act requires a response or not. 
The dialog_act_response.csv tables holds example responses if a response can be generated.

These two files can be edited for more response options.
