# NLP_RecordClassification_Project

The objective of this project is to determine whether two records belong to the same person or not. Various details about individual records like Name, Address, Postcode, date of Birth, etc are provided. The data for this project has been generated synthetically using the Python recordlinkage library. The dataset is: final_dataset.csv

I have used a static Bi-Directional LSTM model to generate character embeddings that can be used to generate an embedding for  each field in the record. The code can be accessed from: Static_Bi-LSTM_Character_Embedding.ipynb

The embedded feature are finally fed into a feed-forward neural network(Multi_Layer Perceptron, MLP) that performs a binary(0 or 1) classification task in order to determine whether two record belong to the same person. The code can be found in: New MLP Model.ipynb
