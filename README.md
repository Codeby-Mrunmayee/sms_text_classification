# 📱 SMS Spam Detection 

This project classifies SMS messages as **ham** (normal message) or **spam** using a neural network built with TensorFlow and Keras. 

## About the Project
- Loaded SMS dataset with labeled messages (train and valid)
- Used TensorFlow’s `TextVectorization` to convert text to tokens
- Built and trained a model with embedding and dense layers
- Created a function to predict if a new message is spam or ham

## Dataset
Includes `train-data.tsv` and `valid-data.tsv` files to reproduce the results.

## Tools Used
- Python  
- TensorFlow / Keras  
- Google Colab

## How to Use
1. Open in Google Colab  
2. Upload dataset files  
3. Run cells to train and test  
4. Use `predict_message()` to classify new texts

## Example Output
Prediction Score: 0.82, Predicted: spam </br>
Prediction Score: 0.01, Predicted: ham


## Author  
Mrunmayee Gore 
