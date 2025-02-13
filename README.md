# Deep Belief Network with Restricted Boltzmann Machine for Image Classification
You have implemented a Deep Belief Network (DBN) using Restricted Boltzmann Machines (RBMs) for the task of plant disease classification. The process involved loading and preprocessing an augmented dataset of plant disease images, normalizing the pixel values, and defining an RBM class to pretrain the layers of the DBN. You pretrained two RBMs sequentially, where the hidden representation of the first RBM was used as input to the second RBM. After pretraining, you constructed the DBN by stacking the RBMs and adding a final softmax output layer for classification. The DBN was then trained on the dataset using early stopping to prevent overfitting. Finally, you evaluated the model's performance on the validation set, generating metrics such as accuracy, confusion matrix, precision, recall, and F1-score to assess its effectiveness in classifying plant diseases.

## Project Structure

- **Model1_DBN_ipynbd.ipynb**: Jupyter notebook containing the implementation of the Deep Belief Network.
- **requirements.txt**: List of Python dependencies to install.
- **.gitignore**: File to ignore unnecessary files in the GitHub repository.

## How to Use

1. Clone this repository:
   ```bash
   git clone (https://github.com/geeranlone/Deep-Belief-Network-with-Restricted-Boltzmann-Machine-for-Image-Classification.git)
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook and run the cells to execute the model.

## Features

- Pretraining and fine-tuning using Deep Belief Networks.
- Evaluation metrics for classification performance.

## License

This project is licensed under the MIT License.
