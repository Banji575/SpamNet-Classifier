# SpamNet-Classifier

SpamNet-Classifier is a sophisticated machine learning project aimed at identifying and classifying spam messages using deep learning techniques. This model is particularly useful in filtering spam from legitimate messages in various applications such as email clients and messaging platforms.

## Technologies Used

- **TensorFlow & Keras**: For building and training the deep learning model.
- **Gensim**: To access pre-trained word embeddings like GloVe.
- **NumPy**: For numerical and array operations.
- **Scikit-Learn**: For metrics computation such as accuracy score and confusion matrix.
- **Python**: The primary programming language for the project.

## Installation

Before running this project, ensure you have Python installed on your system. It's recommended to use a virtual environment for this project to manage dependencies.

1. **Clone the repository**:
```
git clone https://github.com/your-username/SpamNet-Classifier.git
cd SpamNet-Classifier
```

2. **Set up a virtual environment** (optional but recommended):

3. **Install required packages**:
```
pip install tensorflow gensim numpy scikit-learn
```

## Usage

To use the SpamNet-Classifier, follow these steps:

1. **Load your data**: Ensure you have your dataset in a zip file similar to the 'SMSSpamCollection' format.

2. **Train the model**:
Run the training script to train the model on your data. This process may take some time depending on your hardware.

3. **Classify messages**:
Once the model is trained, you can use it to classify messages as spam or not spam. Use the `predict_spam` function by passing in the message, model, tokenizer, and max sequence length.

Example:
```
message = "Free entry in 2 a weekly comp to win FA Cup final..."
print(predict_spam(message, model, tokenizer, max_seqlen))
```

## Contributing
Contributions to SpamNet-Classifier are welcome! Please feel free to submit pull requests or open issues to discuss potential improvements or add new features.

## License

[MIT License](LICENSE)
