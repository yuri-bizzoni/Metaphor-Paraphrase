# Metaphor-Paraphrase

In this repository we present the dataset and the code that we describe in our paper:
"Predicting Human Metaphor Paraphrase Judgments with Deep Neural Networks".

We propose a new annotated corpus for metaphor interpretation by paraphrase, and a novel DNN model for performing this task. 
Our corpus consists of 200 sets of 5 sentences, with each set containing one reference metaphorical sentence, and four ranked candidate paraphrases. 
Our model is trained for a binary classification of paraphrase candidates, and then used to predict graded paraphrase acceptability.

To run our code, W2V word embeddings trained on Google News are needed as an external resource. 
If you have them, you can just change the address lines in the code and run the notebook.
