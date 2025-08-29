Simulating Hallucinations under Psychedelic Magic Mushrooms

This repository accompanies my MSc Data Science dissertation at the University of Bristol:
“Simulating Hallucinations under Psychedelic Magic Mushrooms.”

The project uses Variational Autoencoders (VAEs) with Convolutional Neural Networks (CNNs) to simulate visual alterations akin to psilocybin-induced hallucinations. Perturbations in the latent space and input domain are evaluated against neuroscientific theories of psychedelic effects.

Repository Structure

Notebooks:

VAE+CNN_MNIST_Final.ipynb                # MNIST dataset experiments

VAE+CNN_CIFAR10_Analysis.ipynb           # CIFAR-10 dataset experiments

Datasets

MNIST: Handwritten digit dataset (28x28 grayscale).

CIFAR-10: Natural images across 10 classes (32x32 colour).

Both datasets are publicly available via Torchvision

Perturbations Implemented

Latent Noise Injection – Gaussian noise added in latent space to mimic desynchronization and micro-texture hallucinations.

β-like Prior Modification – Alteration of KL-divergence strength at inference, acting as an anti-hallucination stabilizer.

Input Blur – Kernel-based image blurring, reflecting top-down repair and perceptual regularization.

Metrics

To quantify “hallucination-like” behaviour, the following metrics are computed:

Latent Entropy (H) – randomness of latent codes.

Reconstruction Variability (RV) – pixel variance across repeated reconstructions.

Spectral Slope (α) – characterising spatial frequency flattening linked to psilocybin-induced desynchronization.

License

This repository is for academic and educational purposes only.

