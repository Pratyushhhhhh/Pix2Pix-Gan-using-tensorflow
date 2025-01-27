# Pix2Pix-Gan-using-tensorflow
Deep Learning project || Generative adversarial network (GAN) implementation to colorize images
### Project Summary

This project implements an enhanced Pix2Pix framework to translate input sketches into photorealistic images. The methodology leverages paired datasets, such as the Anime Sketch Colorization Pair and Sketch2Pokemon, for training and evaluation. A U-Net generator and PatchGAN discriminator form the core of the architecture, ensuring high-quality outputs by preserving structural details and enhancing realism.

Key features include:
- **Preprocessing & Augmentation**: Techniques like resizing, normalization, flipping, and rotation improve data diversity and robustness.
- **Loss Functions**: A combination of adversarial loss and L1 loss ensures realism and structural accuracy.
- **Evaluation Metrics**: Metrics such as Fréchet Inception Distance (FID) validate output quality.
- **Applications**: Artistic rendering, image restoration, and creative design.

The implementation was carried out using TensorFlow in Google Colab with GPU acceleration, making it scalable and efficient. Future work could focus on training with larger datasets, optimizing architectures, and expanding to unpaired or real-time scenarios.
