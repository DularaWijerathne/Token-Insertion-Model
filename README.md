# Token Insertion Model

This project entails the development of a neural network model to recognize and predict the positioning of a special token `<X>` within sentences provided by the client. Leveraging the BERT pre-trained large language model and TensorFlow, the project achieved over 90% F1-Score in predicting these patterns. The approach involved preprocessing the data using a BERT tokenizer, building a custom model architecture, and training it to classify token insertion points. Additionally, a function was implemented to automatically insert the `<X>` token into suitable places within sentences based on the trained model's predictions.

## Technologies Used
- TensorFlow
- BERT (Bidirectional Encoder Representations from Transformers)
- Python

## Project Structure
- **Token_Insertion_Model.ipynb**: Jupyter notebook containing the code for data preprocessing, model implementation, and training.
- **Model_Evaluation.ipynb**: Jupyter notebook for evaluating the trained model on testing data and calculating performance metrics.
- **Token_Insertor.ipynb**: Jupyter notebook with a function to insert `<X>` token into text based on model predictions.
- **dataset/**: Directory containing JSON files for training and testing data.
- **output/**: Directory for storing the trained model, evaluation results, and token insertion outputs.

## Acknowledgements
- This project was developed as part of a freelance project for a client.
- The BERT pre-trained model used in this project is from the Hugging Face Transformers library.
