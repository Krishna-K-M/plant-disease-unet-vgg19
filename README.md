# Tea Leaf Disease Detection and Classification using U-Net and VGG19

## Overview

This project focuses on tea leaf disease detection and segmentation using a deep learning architecture that combines U-Net and VGG19. The model identifies diseased regions in tea leaf images using semantic segmentation techniques, helping improve disease monitoring in precision agriculture.

The project was developed using TensorFlow/Keras and trained on annotated tea leaf disease datasets.

---

## Features

- Tea leaf disease detection using deep learning
- Semantic segmentation using U-Net
- VGG19 pretrained encoder backbone
- Image preprocessing and mask generation
- Disease region localization
- TensorFlow/Keras implementation
- Google Colab compatible

---

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Google Colab

---

## Dataset

This project uses the Tea Leaf Disease Dataset from Mendeley Data.

Dataset Link:  
https://data.mendeley.com/datasets/744vznw5k2/4

The dataset contains:
- Tea leaf images
- Disease masks
- Segmentation annotations

---

## Project Structure

```text
Tea-Leaf-Disease-detection-and-classification-using-U-Net-and-VGG19/
│
├── dataset/
│   ├── images/
│   └── masks/
│
├── src/
│   └── App.ipynb
│
├── requirements.txt
├── README.md
├── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Krishna-K-M/plant-disease-unet-vgg19.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Open Jupyter Notebook or Google Colab and run:

```bash
src/App.ipynb
```

---

## Model Architecture

This project uses:

- U-Net for semantic segmentation
- VGG19 as the encoder backbone
- Skip connections for spatial feature recovery
- Pretrained ImageNet weights for feature extraction

---

## Workflow

1. Load tea leaf images and masks
2. Preprocess and resize images
3. Build U-Net with VGG19 encoder
4. Train segmentation model
5. Predict diseased regions
6. Visualize segmented outputs

---

## Output Samples

The model generates:
- Original tea leaf image
- Ground truth mask
- Predicted segmented disease region

Sample outputs can be found in the `outputs/` directory.

---

## Future Improvements

- Real-time disease detection
- Mobile deployment
- Multi-class segmentation
- Web application integration
- Higher accuracy optimization

---

## Author

Krishna K M
