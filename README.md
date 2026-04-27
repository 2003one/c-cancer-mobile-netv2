# c-cancer-mobile-netv2

🚀 This is the first project on my new GitHub — a final year assignment I did during my specialization in Deep Learning, about a year ago. Decided to start fresh and upload it here to document my journey.

About This Project
This project classifies cervical cancer cells from Pap smear images into 5 categories using Transfer Learning with MobileNetV2.
It was part of my final year deep learning specialization, where I worked on medical image classification — one of the most meaningful applications of AI, since it can assist in early detection of cervical cancer.

## The 5 Cell Types

| Class | Cell Type | Description |
|-------|-----------|-------------|
| dys | Dyskeratotic | Abnormal cell — cancer indicator |
| kolio | Koilocytotic | Abnormal cell — HPV related |
| meta | Metaplastic | Transitional cell |
| para | Parabasal | Normal deep layer cell |
| super | Superficial | Normal surface cell |


Dataset

Herlev Pap Smear Dataset
4059 images across 5 classes (~820 per class)
Image size: 326 × 148 pixels
Format: BMP

What I Did

Converted all RGB images to Grayscale (original images untouched)
Trained MobileNetV2 using transfer learning (ImageNet weights)
Two-phase training — head only first, then fine-tuned top layers
Tested predictions on individual images


Tech Stack

Python
TensorFlow / Keras
MobileNetV2 (Transfer Learning)
Pillow
Scikit-learn
Matplotlib
