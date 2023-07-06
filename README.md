# Email_Text_Classification
This project focuses on Text Classification, one of the key tasks in Natural Language Processing (NLP). It explores the NLP techniques of Tokenization, Embedding, and Sequence Modeling, to develop a deep learning model (BERT) that can analyze and predict the sentiment of textual data.

The implementation leverages the BERT model, which is a transformer-based machine learning model proposed by researchers at Google. BERT models are designed to pre-train deep bidirectional representations from an unlabeled text by jointly conditioning on both left and right context in all layers. As a result, the pre-trained BERT model can be fine-tuned with just one additional output layer to create state-of-the-art models for a wide range of tasks.

## Model Features
- BERT Model: The project utilizes the BERT model which is highly capable in understanding the context of a sentence due to its bidirectional nature. It has been proven to be effective in numerous NLP tasks.

- PyTorch Framework: PyTorch, a widely used deep learning framework, has been employed to develop and train the model. It offers flexibility and computational efficiency.

- Fine-Tuning: The pre-trained BERT model is fine-tuned according to our classification needs. Fine-tuning involves training the model on a specific task, like email text classification in our case, after it has been pre-trained on a large corpus of text
