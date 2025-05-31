# Rat Detection CNN

This project implements a Convolutional Neural Network (CNN) for detecting rats in images. The model is trained using a dataset of images containing rats and images without rats.

## Project Structure

- `dataset/`: Contains the training data for the model.
  - `rat/`: Folder with images of rats for training.
  - `no_rat/`: Folder with images without rats for training.
  
- `testing_folder/`: Contains sample images used for testing the trained model.
  - `test_image.jpeg`: A sample image for testing the model's predictions.

- `model/`: Stores the trained CNN model.
  - `rat_cnn_model.h5`: The file where the trained model is saved.

- `rat_detection.ipynb`: A Jupyter notebook that includes:
  - Code for training the CNN model.
  - Evaluation of the model's performance.
  - Making predictions on new images.

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd Rat_Detection_CNN
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Open the `rat_detection.ipynb` notebook in Jupyter.
2. Follow the instructions in the notebook to train the model and evaluate its performance.
3. Use the trained model to make predictions on new images.

## License

This project is licensed under the MIT License.