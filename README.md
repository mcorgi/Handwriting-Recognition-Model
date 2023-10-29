# Handwriting Recognition using CRNN

This project focuses on training a CRNN (CNN+RNN) model for handwriting recognition. The model is trained using the CTC (Connectionist Temporal Classification) loss.

## Technologies Used

- TensorFlow
- Keras
  - Input, Conv2D, MaxPooling2D, Reshape, Bidirectional, LSTM, Dense, Lambda, Activation, BatchNormalization, Dropout

## Data Source

The model was trained using a dataset from Kaggle. For local usage, download the required CSV files from the dataset.

## Usage

### Running Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/handwriting-recognition.git
   ```

2. Download the necessary CSV files from the dataset source and place them in the appropriate directory.

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the main script:

   ```bash
   python main.py
   ```

### Running on a Notebook

1. Open the provided notebook in your preferred environment (e.g., Google Colab).

2. The notebook contains all necessary code and instructions. Simply execute the cells in sequential order.

## Acknowledgements

- Inspiration for this project was taken from the notebook titled "Handwriting Recognition using CRNN in Keras" on Kaggle.
