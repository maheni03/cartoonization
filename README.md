# Cartoonization

**Cartoonization** is a project that uses a Pix2Pix model to transform real-world landscape images into cartoon-styled images. This project was developed as a collaborative effort and includes data, a trained model, and an evaluation pipeline.

## Key Features

- Transform real images into cartoon-style images using Pix2Pix GAN.
- Load and preprocess datasets of paired images.
- Train a generator model on paired real and cartoon images.
- Visualize and evaluate the model's performance with test images.

## Repository Structure

- **`Model/`**: Contains the Pix2Pix model.
- **`cartoon_scenery_images_bis/`**: Cartoon-style images used for training.
- **`original_scenery_images/`**: Real-world images corresponding to the cartoon images.
- **`test_video/`**: test on a video.
- **`new_pix2pix.ipynb`**: Main notebook with training and evaluation code.
- **`.gitattributes`**: Git LFS configuration for handling large files.

## Usage

Training:

Use the new_pix2pix.ipynb notebook to load the data and train the Pix2Pix model.
Prediction:

Load the pre-trained model and use it to generate cartoon-style images from real-world input.
Evaluation:

Measure the quality of transformations using metrics provided in the notebook.

## Authors

- Maheni SOUMAH
- Habiba DJIGO
- Jessica MBOUNKAP
- Tasnim MASHEH
