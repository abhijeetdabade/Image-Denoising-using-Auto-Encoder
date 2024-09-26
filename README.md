
# Denoising Autoencoder

This project demonstrates the implementation of a Denoising Autoencoder using the MNIST dataset. 
The autoencoder is trained to remove noise from images by reconstructing the original images from noisy inputs.

## Requirements
- Python 3.x
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib

## Dataset
The MNIST dataset, consisting of handwritten digits, is used for training the autoencoder.

## Steps
1. Load the MNIST dataset.
2. Add random noise to the images.
3. Build a convolutional autoencoder model.
4. Train the model on the noisy images.
5. Evaluate the model by reconstructing the clean images from noisy inputs.

## Usage
1. Install the dependencies using `pip install -r requirements.txt`.
2. Run the notebook to train the autoencoder and view the reconstructed images.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
