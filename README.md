# Spam-and-Ham-text-classifier
In this project, we are using LSTM to classify texts as spam or ham.

<p align="center">
  <img width="480" height="280" src="https://github.com/AHMEDSANA/Spam-and-Ham-text-classifier/assets/73955220/8b59b9dc-366e-4459-bcc2-d818238bf033">
</p>

### Spam messages classification using LSTM
Spam or ham classification is a task where we determine whether a given SMS message is spam (unsolicited or unwanted) or ham (non-spam). This can be achieved using LSTM (Long Short-Term Memory) neural networks, which are effective in processing sequential data like text. By training an LSTM model on a labeled dataset of SMS messages, we can build a classifier that can predict whether new messages are spam or ham. The process involves data preparation, text preprocessing, word embeddings, model architecture design, training, evaluation, and deployment.

### Data Preparation:

Collect a labeled dataset of SMS messages with corresponding labels indicating whether each statement is spam or ham. Split the dataset into training and testing sets.

<p align="center">
  <img width="360" height="228" src="https://github.com/AHMEDSANA/Spam-and-Ham-text-classifier/assets/73955220/e8c83f0d-95b8-482f-81f2-f75effb7e7dc">
</p>

### Text Preprocessing:
Preprocess the SMS messages by performing tasks such as tokenization, lowercasing, removing punctuation, and removing stop words (optional). You may also consider stemming or lemmatization depending on your specific requirements.

<p align="center">
  <img width="360" height="228" src="https://github.com/AHMEDSANA/Spam-and-Ham-text-classifier/assets/73955220/cc630b86-55d7-4b37-aa8e-40eed385f680">
</p>

### Word Embeddings:
Convert the preprocessed text data into numerical representations that capture semantic meaning. Use word embeddings like Word2Vec or GloVe to represent each word as a dense vector.

<p align="center">
  <img width="" height="" src="https://github.com/AHMEDSANA/Spam-and-Ham-text-classifier/assets/73955220/652fd612-63b0-4e6e-aa5e-398597578674">
</p>

### Padding: 

Since LSTM networks require inputs of the same length, pad or truncate the sequences to a fixed length. Ensure that all SMS messages have the same length by adding padding (zeros) or truncating the text.

### Model Architecture:

Define an LSTM-based architecture for the spam classification task. Typically, this involves stacking LSTM layers followed by a final dense layer with a sigmoid activation function to produce binary predictions.

<p align="center">
  <img width="" height="" src="https://github.com/AHMEDSANA/Spam-and-Ham-text-classifier/assets/73955220/c6b5a4ec-994e-48e5-a4d5-b3a9a7a26838">
</p>

### Model Training:
Train the LSTM model on the preprocessed and padded SMS messages. Use appropriate loss functions (e.g., binary cross-entropy) and optimization algorithms (e.g., Adam or RMSprop) to train the model. Monitor the training process and adjust hyperparameters if needed.

<p align="center">
  <img width="" height="" src="https://github.com/AHMEDSANA/Spam-and-Ham-text-classifier/assets/73955220/ed0cf225-3aa8-4a84-8c52-adc8001dcde4">
</p>

### Model Evaluation:
Evaluate the trained model on the testing set to measure its performance. Standard evaluation metrics include accuracy, precision, recall, and F1-score. Could you look over the results to assess the model's effectiveness in distinguishing spam from ham messages?

<p align="center">
  <img width="" height="" src="https://github.com/AHMEDSANA/Spam-and-Ham-text-classifier/assets/73955220/fb9f3ed9-9183-4aa9-a427-e658582d0aaf">
</p>

### Test Texts

<p align="center">
  <img width="" height="" src="https://github.com/AHMEDSANA/Spam-and-Ham-text-classifier/assets/73955220/f8388a82-95ec-4ed1-8102-65a8171ce54a">
</p>

### Predictions
<p align="center">
  <img width="" height="" src="https://github.com/AHMEDSANA/Spam-and-Ham-text-classifier/assets/73955220/d555ce8a-be45-44ba-98a6-731de3cbbd47">
</p>

### Deployment:

Integrate the trained LSTM model into an application or system that can accept new SMS messages and classify them as spam or ham in real time.

### How to run code:
You can just run the code by copying the code from the Python notebook file or by downloading and running the file.
The dataset link is already in the notebook file so it will be downloaded during the running process.
