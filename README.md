# Question-Answering-with-Hugging-Face

An attempt to understand the Question-Answering problems in the NLP domain while using the pre-trained models from Hugging Face. 
Here, we have compared 3 different models for the problem:
  1. Using the pre-trained deepset/bert-base-cased-squad2 from Hugging=Face Repository (Which performs the best)
  2. Using the pre-trained model by training the dataset ourselves on a distilbert-base-uncased model and adding it to the Hugging Face repository so that we can use it      at any time. (Performs second best)
  3. Using only the base model from distilbert-base-uncased to answer the questions in the Question-Answering Pipeline.
