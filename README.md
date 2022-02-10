# Vorpal Dictionary

A Python Tensorflow/Keras LSTM neural network generates new adjectives that sound generally plausible as real words. The words it creates are saved and the user is prompted to provide two inputs for each word: a definition and an example of its use. The loop of word inputs can currently be broken by entering the word "exit" when prompted for a definition. The script then puts this information together into a full dictionary entry for each word that the user defined, saved into another text file.

Model was trained on a collection of real adjectives from [this dataset](https://www.kaggle.com/jordansiem/adjectives-list). Many thanks to the creator of the dataset
