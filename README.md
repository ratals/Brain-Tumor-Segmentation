# Brain-Tumor-Segmentation

An efficient deep learning model using the UNet architecture to accurately segment brain tumors from MRI images, and integrate the model with a Web-based user interface for real-time image analysis and visualization.

This Objective includes several key components:
1. Data Preparation: Explore and preprocess the BraTS2020 dataset, including MRI modalities (T1, T1ce, T2, FLAIR) and their corresponding segmentation masks.
2. Model Development: Design a UNet-based deep learning model for segmenting brain tumors using multimodal MRI data.
3. Data Normalization: Implement data scaling and normalization to ensure uniformity across modalities for improved model performance.
4. Training & Validation: Train the model on the BraTS2020 dataset and validate its accuracy using performance metrics like the Dice coefficient and IoU.
5. Front-End Interface: Develop a Web Application for real-time interaction with the segmentation model, allowing users to upload and visualize MRI images and tumor segmentations.
6. Model Evaluation & Optimization: Fine-tune the model by experimenting with different hyperparameters and modality combinations to optimize accuracy.
7. Result Visualization: Visualize and compare predicted tumor regions with ground truth masks within the Web app.
8. Future Scope: Ensure scalability for future applications in medical image segmentation tasks and clinical workflows.

## About the Dataset (The BraTS2020 Dataset)
The BraTS2020 (Brain Tumor Segmentation 2020) dataset is a key resource for developing and evaluating brain tumor segmentation models. It includes multimodal MRI scans from glioma patients, offering four imaging modalities:
• T1-weighted (T1)
• Post-contrast T1-weighted (T1ce)
• T2-weighted (T2)
• T2-FLAIR (Fluid Attenuated Inversion Recovery)
Each modality provides different insights into tumor characteristics and surrounding tissue. The dataset also includes expert-annotated segmentation masks that classify tumor regions into:
1. Label 0: Not Tumor (NT) volume
2. Label 1: Necrotic and non-enhancing tumor core (NCR/NET)
3. Label 2: Peritumoral edema (ED)
4. Label 3: Missing (No pixels in all the volumes contain label 3)
5. Label 4: GD-enhancing tumor (ET)
These annotations are crucial for training deep learning models, as they provide the ground truth needed for accurate model evaluation.

## Challenges in Brain Tumor Segmentation
Segmentation of brain tumors presents several challenges:
- Tumor Variability: Tumors differ greatly in shape, size, and appearance, complicating segmentation efforts.
- Data Imbalance: Tumor regions occupy a relatively small portion of MRI scans compared to healthy tissue, leading to imbalanced class distributions.
- Image Noise and Overlapping Tissues: MRI scans can include noise and overlapping tissues, which can interfere with accurate segmentation.

## Applications and Future Prospects
Automatic brain tumor segmentation has numerous applications:
- Support for Radiologists: Provides additional insights and reduces the time required for manual analysis.
- Surgical Planning: Helps in identifying tumor boundaries for precise surgical interventions.
- Treatment Monitoring: Enables tracking of tumor progression or response to treatments.
