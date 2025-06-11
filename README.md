#  Human image Segmentation with UNet (MADS Dataset)

This project performs full-body **human segmentation** using a lightweight **UNet-based CNN model**, trained on the **MADS dataset**. The pipeline includes image loading, preprocessing, training, validation, and mask prediction — all optimized for use in Google Colab or local environments.

---

##  Dataset

**MADS - Full Body Human Segmentation Dataset**  
📍 Kaggle link: [https://www.kaggle.com/datasets/tapakah68/segmentation-full-body-mads-dataset](https://www.kaggle.com/datasets/tapakah68/segmentation-full-body-mads-dataset)
🤖 Model: Download best_unet_mads.keras in the repo
- 1192 images with corresponding binary masks
- Multiple classes of human poses and actions
- High-quality segmentation masks for supervised training

---

##  Features

- Lightweight custom **UNet** architecture (32–256 filters)
- Trained with `binary_crossentropy`, evaluated with **accuracy** and optional **IoU**
- Early stopping and best model saving
- Supports `.h5` and `.keras` model formats
- Image upload support for prediction (no webcam needed)
- Visual output of segmented masks in Colab

---


