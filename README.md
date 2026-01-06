# Pedestrian and Vehicle Instance Segmentation Based on Mask2Former

This project applies Mask2Former to pedestrian and vehicle instance segmentation on the Cityscapes (COCO-style) dataset.

## Description
The project focuses on dataset adaptation, category reduction (80 → 10), and training pipeline setup under limited computational resources. 
ResNet-50 is used as the backbone, and stable convergence is achieved through iterative training and hyperparameter tuning.

## Notes
- Dataset and model weights are not included.
- This repository focuses on engineering practice and training pipeline configuration.

## Acknowledgement
This project is based on Mask2Former.

## output
<img width="640" height="480" alt="ap_curve" src="https://github.com/user-attachments/assets/93d064ce-aed9-4dd1-b1ae-5ba51ed65528" />
<img width="640" height="480" alt="loss_curve" src="https://github.com/user-attachments/assets/d7948b8c-b7a1-4d2b-aaea-aa0e7ecd7b71" />

## result
<img width="2048" height="1024" alt="vis_pred_0" src="https://github.com/user-attachments/assets/593ece94-055f-4b9a-a559-83602c3de4a9" />
<img width="2048" height="1024" alt="test_img_0" src="https://github.com/user-attachments/assets/be8bca49-2f5d-4513-8a83-3e36d9d0631e" />
