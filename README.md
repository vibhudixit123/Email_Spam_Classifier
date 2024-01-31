
# Email Spam Classifier with Embeddings and Neural Network 

This repository contains the code and documentation for an email spam classifier developed using embeddings and a neural network. The project aims to accurately classify emails as spam or non-spam using the spam.csv dataset. The model utilizes embeddings to capture semantic meaning and a neural network for classification.


## Screenshots
![Screenshot 2024-01-31 202418](https://github.com/vibhudixit123/Email_Spam_Classifier/assets/104568465/bfa9c4e5-0f42-4e20-acc8-feddc9c89cb1)

![Screenshot 2024-01-31 203857](https://github.com/vibhudixit123/Email_Spam_Classifier/assets/104568465/66589ddf-7b1c-4f00-8318-8a93bcdc3823)



## Data
The dataset used for training is stored in spam.csv. This dataset contains email messages labeled as spam or non-spam, providing the necessary information for training the email spam classifier.
## Model Architecture:
The email spam classifier employs the following architecture:

Embeddings Layer:

Converts each word in the email messages into dense vectors to capture semantic meaning.
Embeddings provide a more nuanced representation of words compared to traditional one-hot encoding.

Neural Network:

A sequential neural network is utilized for classification.
The architecture may include one or more hidden layers with activation functions like ReLU.
The output layer uses a sigmoid activation function for binary classification (spam or non-spam).
## Training and Evaluation:

The model is trained on the spam.csv dataset, using 50 epochs and early stopping to prevent overfitting. Performance metrics such as accuracy, precision, recall, and F1 score are evaluated to assess its effectiveness in classifying spam emails.
## License

[MIT](https://choosealicense.com/licenses/mit/)

