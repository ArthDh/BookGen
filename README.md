# BookGen
Generate text in the style of a book. This is a character level model which predicts the next character based on previous characters of specified size. The model used is stacked LSTM network so as to preserve the order of longer sentences.

# Dependencies
* Keras (Tensorflow Backend)
* Numpy

# Usage
1. Upload the text corpus of your choice in /data folder
1. Run LSTM_GOT.ipynb locally
1. Change the data_path variable to your text corpus name
1. Train for atleast 20 epochs
1. Use predict to generate novel text
