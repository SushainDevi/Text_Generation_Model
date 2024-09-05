
# Text Generation Model

This project implements a text generation model using TensorFlow for generating text similar to a given input. The model is trained on the Tiny Shakespeare dataset and is capable of generating text character by character.

## Model Overview

The text generation model is built using TensorFlow and consists of the following components:

- **Dataset**: The Tiny Shakespeare dataset is used for training the model.
- **Preprocessing**: The text data is preprocessed and converted into numerical representations.
- **Model Architecture**: The model architecture includes an Embedding layer, LSTM (Long Short-Term Memory) layer, and a Dense layer.
- **Training**: The model is trained using the Adam optimizer and sparse categorical cross-entropy loss function.
- **Text Generation**: After training, the model can generate text given an initial input string.

## Usage

To execute the text generation model:

1. Clone this repository to your local machine:

    ```bash
    git clone <https://github.com/SushainDevi/Text_Generation_Model.git>
    ```

2. Install the required libraries:

    ```bash
    pip install tensorflow tensorflow_datasets
    ```

3. Open the provided Jupyter Notebook (`Text_Generation_model.ipynb`) in a Jupyter environment (e.g., Google Colab or Jupyter Notebook).

4. Execute each cell in the notebook to train the model and generate text.

## Contributors

- [Sushain Devi](https://github.com/SushainDevi)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README according to your project's specifics. Let me know if you need further assistance!
