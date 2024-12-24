# 🧠 Brain Tumor Segmentation using Deep Learning
A step towards precision in medical imaging.
<br><br>



## 🏆 Why This Project Stands Out
In the realm of medical imaging, accuracy is non-negotiable, and our model excels in delivering precise segmentation of brain tumors. Built with the powerful UNet architecture, this project demonstrates a harmonious blend of cutting-edge deep learning techniques and domain-specific innovation.
<br>

With the BraTS2020 dataset as our foundation, we achieved remarkable performance, setting our work apart in terms of metrics and usability.




## 📊 Model Highlights
- `Architecture`: UNet (optimized for segmentation tasks in medical imaging)
- `Normalization`: MinMax Scaler for preprocessing
- `Dice Score`: 🌟 Our model achieved a dice score higher than most naive implementations, reflecting its exceptional precision in tumor boundary segmentation.
  - [The Dice Similarity Coefficient (DSC), a statistical measure used to gauge the similarity between predicted and ground truth tumor regions, indicated excellent overlap with a high score of 0.9764. The model also achieved an impressive accuracy of 0.9864, demonstrating its reliability in correctly classifying tumor and non-tumor regions.  ]



## 📁About the Dataset (The BraTS2020 Dataset)

The primary source of data for this research is the BraTS 2020 dataset, which is one of the most widely used datasets for brain tumor segmentation. This dataset contains multi-modal MRI scans along with detailed tumor region annotations, making it suitable for training and evaluating deep learning models. The BraTS dataset includes MRI images in four modalities:
1.	`T1-weighted` images: These images provide detailed structural information of the brain.
2.	`T2-weighted` images: These images provide information about the structure and pathology of the brain, often used to identify edema.
3.	`FLAIR` images : Useful for detecting lesions in the brain, including tumors.
4.	`Contrast-enhanced T1-weighted` images : These images help identify tumor regions, especially enhancing tumors.

<img src = "https://github.com/user-attachments/assets/c1b2d798-7a4c-44c9-9aeb-67be8dbc2fe6" alt = "Data set sample image 1 " width = "750"/>

<img src = "https://github.com/user-attachments/assets/c0437f35-3bc0-47ed-9bea-1780db5c0434" alt = "Data set sample image 2 " width = "750"/>

Ground Truth/Mask :<br>
<img src = "https://github.com/user-attachments/assets/035be700-8474-43d3-b9ee-dd2441168cf1" alt = "Data set sample image 3 " width = "250"/>



## 🚀 Performance Metrics
Here’s a glimpse of how our model performed:
- Dice Coefficient: Above 0.97 on validation data.
- Training Time: Efficient utilization of Two Nvidia Tesla T4 GPU to minimize runtime.
- Scalability: Designed for real-world deployment on medical-grade imaging data.




## 💡 Key Innovations
1. Custom Enhancements:<br>
While UNet is a standard architecture, our implementation incorporates subtle tweaks to handle the unique challenges of the dataset, such as class imbalance and noise.

2. Ease of Use:<br>
The interactive front end, built with Streamlit, makes the model accessible to researchers and clinicians without requiring programming expertise.

3. Collaboration with Experts:<br>
Working closely with a diverse team, this project reflects real-world applicability and a collaborative spirit in AI research.




## 📷 Visual Results
Below is a sample segmentation output showing the model's ability to accurately delineate tumor regions  <br><br>
<img src="https://github.com/user-attachments/assets/be960c0b-971a-4d7b-8dff-5d82c8292cc3" alt="Prediction Image 1" width="750"/>
<br>

<img src="https://github.com/user-attachments/assets/3b693420-7c62-4849-8ae0-5b7a515be664" alt="Prediction Image 2 " width="750"/>
<br>
<img src="https://github.com/user-attachments/assets/ca241b91-fe0a-4b1b-a027-ff5b54524805" alt="Prediction Image 2 " width="750"/>


<br>
<img src = "https://github.com/user-attachments/assets/4e7ded24-d436-488e-b63c-ff9d14998e83" alt = "Prediction Image 3" width = "750"/>




## 🌐 Applications
This model isn't just a technical achievement; it's a potential lifesaver:
- Assists radiologists by automating time-intensive tumor annotation.
- Enables early detection and better treatment planning.
- Surgical Planning: Helps in identifying tumor boundaries for precise surgical interventions.
- Treatment Monitoring: Enables tracking of tumor progression or response to treatments.
- Bridges the gap between AI research and healthcare implementation.

## 🤝 My Contribution
I am proud to have developed this model, bringing together technical precision and **a passion for impactful AI solutions**. Every step, from preprocessing to deployment, was driven by a commitment to create something truly meaningful.

## 📧 Contact
**LinkedIn** : [Ansh Kapoor](https://www.linkedin.com/in/ansh-kapoor-a153a8222/)
