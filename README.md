# English-to-French-Translator
Developed an English to French Translator using RNNs, handling a vocabulary of 227 English and 355 French words, with a training accuracy of 93.97% and validation accuracy of 93.82%. The model processed sentences up to 15 words in English and 21 words in French.


This project involves developing an end-to-end machine translation pipeline using Recurrent Neural Networks (RNNs) to translate English sentences into French. The model is built using the Keras library and utilizes a sequence-to-sequence architecture.

Key Features

Vocabulary Size: The dataset consists of 227 unique English words and 355 unique French words.

Sequence Length: The model can handle English sentences up to 15 words and French sentences up to 21 words.

Model Architecture: The architecture includes an embedding layer, GRU layer, and time-distributed dense layers to effectively process and generate translations.

Training Metrics: The model was trained for 20 epochs with a batch size of 1024, achieving a training accuracy of approximately 93.97% and a validation accuracy of 93.82%.

Prediction Interface: The model is integrated with Gradio to provide an interactive interface for users to input English text and receive French translations in real-time.

Technologies Used

Keras: For building and training the neural network model.

TensorFlow: As the backend for Keras.

Gradio: For creating the interactive prediction interface.

Python: As the primary programming language.

Project Structure

Data Preprocessing: Tokenization and padding of input sequences.

Model Development: Design and implementation of the RNN model.

Training: Training the model with specified hyperparameters.

Deployment: Integration with Gradio for interactive predictions.
