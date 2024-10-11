Description
This repository contains two primary models: a detector model to identify pixelated images and a depixelator model to restore pixelated images to their original quality. Both models were inspired by the U-Net architecture but optimized for efficiency using depthwise and pointwise convolutions.

Repository Structure


Testing Files
detector_testing.ipynb
depixelator_testing.ipynb
These are the testing files. Users should follow the instructions in these files to test our detector and depixelator models.

Step-by-Step Guide to Test Our Models

Update and Import Libraries: Ensure all required libraries are updated to the necessary versions and import them.

Load the Models: Load the pre-trained detector or depixelator model.

(Important) Implement the TODO Cell: Complete the TODO cell according to your own dataset, defining image_paths and image_labels or pixelated_image_paths, and optionally real_image_paths.

Test the Model: Follow the steps provided in the testing files to effectively test the models on your dataset.

Training Files
detector_training.ipynb
depixelator_training.ipynb
These are the training files used for our detector and depixelator models. They are included for reference to show how we trained our models.

Model Architectures
detector_005_1.png
depixelator_004_2.png
These images depict the detailed architectures of our models.

Pre-trained Models
detector_005_1_50.keras
depixelator_004_2.keras
These files contain the pre-trained models with their corresponding architectures.


Conclusion
This repository offers a comprehensive solution for detecting and depixelating images, utilizing state-of-the-art techniques for efficiency and accuracy. By following the provided instructions and completing the required steps, users can effectively apply these models to their datasets to achieve high-quality image restoration.

