# Applying deep learning to categorize free-form text within a budget framework

# About this project
An overview of the project is documented in final.pptx. The project is based on a [competition](https://www.drivendata.org/competitions/46/box-plots-for-education-reboot/) on drivendata.org.

# Running the code
Multiple classification approaches were tested in this project. All code and required data are self-contained within individual folders for each approach.
- datacamp_model: bag of words representation fed into logistic regression
- basic_NN_model: bag of words representation fed into feedforward network
- CNN_NN_model: bag of words representation fed into convolutional network
- embedding_NN_model: word embeddings representation fed into convolutional network
- GRU_NN_model: word embeddings representation fed into recurrent network

EDA contains exploratory data analysis steps.

# Folder Contents
In each approach folder, you will find the following files
- {approach}.json: code the run
- {approach}.json: model architecture
- {approach}.h5: trained model weights
- {approach}.csv: predictions
- {approach}_score.json: logloss score for each label
- resources.zip: raw data provided by competition
- tokenizer.pickle: tokenizer used to tokenize text data
- X_train_numeric.npz: processed numeric feature data (training set)
- X_val_numeric.npz: processed numeric feature data (validation set)
- X_test_numeric.npz: processed numeric feature data (test set)
- X_train_text.npz: processed text feature data (training set)
- X_val_text.npz: processed text feature data (validation set)
- X_test_text.npz: processed text feature data (test set)
- y_train.npz: training set labels
- y_val.npx: validation set labels
