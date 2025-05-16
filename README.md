## Project Overview

This project contains a collection of deep learning models and practical implementations across four major areas:

* **AutoEncoder** for data compression and reconstruction
* **Classification** for image recognition (e.g., MNIST)
* **GAN (Generative Adversarial Networks)** for image generation
* **Segmentation** for pixel-level image labeling

Each directory includes code and resources to help you understand and apply key deep learning techniques in a hands-on way.

---

## Project Structure

```
UR_git/
├── AutoEncoder/         # Autoencoder models and training scripts
├── Classification/      # Image classification with MNIST and model training
├── GAN/                 # GAN training and experiment scripts
├── Segmentation/        # Image segmentation models (e.g., U-Net)
└── README.md            # Project description and usage instructions
```

---

## How to Run

Each module may have its own setup, but in general, all scripts are written in Python. You can install the required libraries using `pip` or a provided `requirements.txt` file.

### 1. Install Dependencies

```bash
pip install -r requirements.txt
# Or install manually:
pip install torch torchvision matplotlib numpy
```

### 2. Run AutoEncoder Example

```bash
cd AutoEncoder
python train_autoencoder.py
```

### 3. Run Classification Example

```bash
cd Classification/code
python MNIST_dataset.py
python train_classifier.py
```

### 4. Run GAN Example

```bash
cd GAN
python train_gan.py
```

### 5. Run Segmentation Example

```bash
cd Segmentation
python train_unet.py
```

---

## Notes

* Each folder may contain its own `README.md`, datasets, or training scripts.
* Make sure to verify any required dataset paths or adjust configuration settings before running.
* Python 3.8+ and PyTorch 1.10+ are recommended for compatibility.
