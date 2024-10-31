# Oil Spill Detection Using Deep Learning
## Project Overview
This project applies deep learning to detect and segment oil spills in satellite images. Using U-Net and DeepLabV3 architectures, it performs pixel-level segmentation to identify oil spills, supporting efficient environmental monitoring.

## Installation
Clone the repository using git:
```bash
git clone https://github.com/Prajwal2212/Oil-Spill-Detection-CVT.git
cd oil-spill-detection
```

## Dataset
The dataset consists of satellite images with corresponding segmentation masks for training and testing. Each mask highlights oil spill regions, making it suitable for supervised learning.
<img width="667" alt="image" src="https://github.com/user-attachments/assets/564a19b8-661c-4297-a7f9-0fc5bfe9138d">

## Models
### U-Net: 
A CNN architecture designed for precise segmentation, ideal for identifying small or complex shapes like oil spills.
<img width="1225" alt="image" src="https://github.com/user-attachments/assets/56f35693-dbd0-48ed-bc06-d5d8e0baa99e">

### DeepLabV3: 
Uses atrous convolutions to capture multi-scale context, performing well in complex environments.
<img width="1214" alt="image" src="https://github.com/user-attachments/assets/173b7ffd-2f76-4fa1-9880-08d64bcaddf7">

## Results
The project visualizes model performance on test images and provides evaluation metrics like confusion matrices for segmentation accuracy.
<img width="1201" alt="image" src="https://github.com/user-attachments/assets/1181eea3-4187-401b-add6-4f5ad89164b7">
