# 🌿 Plant Disease Detection and Classification using U-Net and VGG19

## 📌 Overview

An end-to-end deep learning pipeline for detecting and classifying plant
diseases from leaf images. The project combines **U-Net** for
segmentation and **VGG19** for classification to improve accuracy by
focusing on infected regions.

------------------------------------------------------------------------

## 🚀 Key Features

-   Leaf disease **segmentation** using U-Net
-   Disease **classification** using transfer learning (VGG19)
-   Clean **notebook-based workflow** (App.ipynb)
-   Modular pipeline: preprocessing → segmentation → classification →
    evaluation

------------------------------------------------------------------------

## 🧠 Architecture

### U-Net (Segmentation)

-   Encoder--decoder with skip connections
-   Produces pixel-wise masks of infected regions

### VGG19 (Classification)

-   Pretrained on ImageNet
-   Fine-tuned on plant disease data
-   Uses segmented outputs for better feature focus

------------------------------------------------------------------------

## 📂 Project Structure

    .
    ├── App.ipynb          # Main implementation notebook
    ├── README.md          # Documentation

------------------------------------------------------------------------

## ⚙️ Requirements

Install dependencies:

    pip install numpy pandas matplotlib opencv-python tensorflow keras scikit-learn

------------------------------------------------------------------------

## ▶️ Usage

1.  Clone the repo

```{=html}
<!-- -->
```
    git clone  https://github.com/Krishna-K-M/plant-disease-unet-vgg19.git
    cd plant-disease-unet-vgg19

2.  Launch notebook

```{=html}
<!-- -->
```
    jupyter notebook App.ipynb

3.  Run cells sequentially

------------------------------------------------------------------------

## 🔄 Workflow

1.  Data loading & preprocessing\
2.  Train/Load U-Net for segmentation\
3.  Generate masks for images\
4.  Train/Load VGG19 for classification\
5.  Evaluate predictions

------------------------------------------------------------------------

## 📊 Outputs

-   Segmented leaf images (masks)
-   Predicted disease labels
-   Performance metrics (accuracy/loss)

------------------------------------------------------------------------

## 🎯 Applications

-   Precision agriculture
-   Early disease detection
-   Automated crop monitoring systems

------------------------------------------------------------------------

## 🔮 Future Work

-   Deploy as web app (Flask/Streamlit)
-   Real-time camera inference
-   Expand dataset & augmentations
-   Try EfficientNet/ViT

------------------------------------------------------------------------

## 📜 License

For academic and research purposes.
