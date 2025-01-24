# Image Classification with CNN for Malaria Data

This project classifies microscopic cell images into parasitized or uninfected categories using a Convolutional Neural Network (CNN). Data augmentation and early stopping techniques are applied to enhance performance and prevent overfitting.

## Contents
- **Data Loading and Preprocessing**  
  - Resizing images to 64×64  
  - Normalizing pixel values  
  - Labeling based on directory structure (Parasitized = 1, Uninfected = 0)  
- **Model Building**  
  - CNN architecture with convolution, max-pooling, batch normalization, and dropout layers  
- **Model Training**  
  - Train/test split using train_test_split  
  - Data augmentation: rotation, shifting, flipping, zooming  
  - Early stopping to avoid overfitting  
- **Evaluation and Saving**  
  - Model accuracy and loss validation  
  - Option to save the trained model as an .h5 file

## Usage
1. Clone or download this repository.  
2. Install required Python libraries (TensorFlow, NumPy, Pillow, etc.).  
3. Open and run all cells in the Jupyter Notebook file “Image-Classification-with-CNN-for-Malaria-Data.ipynb”.  
4. Check the project folder for the saved .h5 model file after training completes.

## License
This project is intended for educational and research use. Please see the license file for details.
