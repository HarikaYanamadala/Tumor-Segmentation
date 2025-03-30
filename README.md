# Tumor-Segmentation
This project implements a brain tumor segmentation model using a UNet architecture with EfficientNetB7 as the encoder. The model is trained on medical MRI datasets to accurately segment brain tumors.

-->Features

Deep Learning-based segmentation using UNet

Pretrained EfficientNetB7 encoder for feature extraction

Optimized for real-time inference (0.08 sec/image on RTX 3090)

Deployment-ready with Flask/FastAPI API support

-->Dataset

Sources: BraTS, Open Source Brain, PhysioNet

Total Images: 5,000 MRI scans

-->Preprocessing:

Resized to 256×256

Normalization using ImageNet mean/std

Data augmentation (rotation, flipping, intensity shifts)

-->Model Architecture

UNet-based architecture with EfficientNetB7 as the encoder

Decoder with skip connections for spatial accuracy

Sigmoid activation for binary segmentation

-->Results

Dice Similarity Coefficient (DSC): 91.8%

Sensitivity: 90.5%

Specificity: 93.2%

Hausdorff Distance: 6.2 mm

-->Future Enhancements

Multi-modal integration (MRI + CT scans)

Edge AI Deployment (mobile, low-power devices)

Self-supervised learning for better generalization

