# RNN Seq2Seq Model for Urdu Language Translation

This Github repository contains the implementation of a Recurrent Neural Network (RNN) Seq2Seq model for translating text from Roman Urdu to Urdu. This project was completed as part of the Natural Language Processing (NLP) course for a Bachelor's degree.

## Data

The training data is available in two files: `roman_urdu.txt` and `urdu.txt`. The `roman_urdu.txt` file contains Roman Urdu text, while `urdu.txt` contains the corresponding Urdu translations.

## Model

We implemented an RNN Seq2Seq model for text translation using PyTorch, following the [official tutorial](https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html) from the PyTorch documentation. The model is trained on the provided training data and is able to translate Roman Urdu text into Urdu.

## Code

The code for the implementation of the model can be found in the `seq2seq_translation.ipynb` Jupyter notebook. This file contains the implementation of the RNN Seq2Seq model and the training process.

## Requirements

The following packages are required to run the code in this repository:

- PyTorch
- Numpy

## Usage

To use the model to translate Roman Urdu text into Urdu, open the `seq2seq_translation.ipynb` notebook in Jupyter and run the cells. The notebook will load the training data, preprocess it, build the RNN Seq2Seq model, and train the model on the data. After training, the notebook will generate sample translations to evaluate the model's performance.

## Contributing

Contributions to this project are welcome. If you find any issues or would like to suggest any improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://github.com/WaleedK2000/SEQ2SEQ_RNN/blob/main/LICENSE).
