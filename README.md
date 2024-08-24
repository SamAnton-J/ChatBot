# Chatbot Project

## Overview

This project is a chatbot that leverages machine learning techniques to understand and respond to user queries. It uses TensorFlow and Keras for building the model and scikit-learn for preprocessing. The chatbot is designed to handle various conversational inputs and provide relevant responses.

## Features

- Text preprocessing and tokenization
- Neural network model for intent classification
- Label encoding for categorical outputs
- Responses based on user input

## Requirements

- Python 3.x
- TensorFlow 2.x
- Keras 3.x
- scikit-learn
- NumPy
- Pickle

You can install the required packages using pip:

```bash
pip install tensorflow scikit-learn numpy
```

## Usage

1. **Prepare your data**: Ensure your training data is in the proper format. You should have a dataset with input texts and corresponding intent labels.

2. **Train the Model**: Run `model.py` to train the model on your dataset.

   ```bash
   Model_training.ipynb
   ```

3. **Interact with the Chatbot**: Run `chatbot.py` to start the chatbot and interact with it.

   ```bash
   chatbot.py
   ```

4. **Saving and Loading the Model**: The trained model and tokenizer will be saved in the `data/` directory. Use `pickle` to save and load these files as needed.

## Code Explanation

- **Imports**: The project uses `json`, `numpy`, `tensorflow`, `keras`, and `sklearn` for various tasks including data processing, model building, and encoding.

- **Model Architecture**: The chatbot model uses a Sequential neural network with embedding layers, dense layers, and global average pooling.

- **Text Preprocessing**: The text data is tokenized and padded to ensure consistent input shapes for the model.

- **Label Encoding**: Intent labels are encoded using `LabelEncoder` to convert them into numerical format suitable for model training.

## Contributing

Feel free to fork the repository and submit pull requests. If you encounter any issues or have suggestions for improvements, please open an issue on GitHub.

## Contact

For any questions or inquiries, please contact [jsam2k4.pro.com].

```

Feel free to adjust any parts of this `README.md` to better fit the specifics of your project!
