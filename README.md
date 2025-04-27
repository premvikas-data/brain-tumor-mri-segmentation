Dataset Link- https://www.kaggle.com/datasets/nikhilroxtomar/brain-tumor-segmentation/data
# Brain Tumor Segmentation from MRI Images 🧠

This research project implements deep learning-based methods to automate brain tumor segmentation from MRI images. We compare Convolutional Neural Networks (CNNs), traditional K-means clustering, and advanced UNet architectures, including batch-normalized UNets, to identify and segment tumors efficiently and accurately.

## Project Highlights
- 📄 Thesis: "Segmentation Model for Brain Tumor Using MRI" (MSc Thesis at Munster Technological University)
- 🧠 MRI-based brain tumor segmentation with deep learning
- 📊 Model Comparison: CNN, K-means, UNet, UNet + Batch Normalization
- 📈 Metrics: Dice Coefficient, IoU, Accuracy, Hausdorff Distance, AUC
- 🧪 Cross-validation (5-fold) for robust model evaluation
- 🎯 Achieved highest performance using UNet with batch normalization

## Technologies Used
- Python (TensorFlow, Keras, Scikit-Learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Medical Image Preprocessing
- CNNs, UNet, K-means Clustering

## Dataset
- 3064 MRI brain images with corresponding ground truth segmentation masks
- Sourced from a public NCBI repository
- Data split into train, validation, and test sets with preprocessing and augmentation

## Future Enhancements
- Attention-UNet and Transformer-based models
- Integration with real clinical imaging pipelines
- Cross-attention mechanisms for improved boundary detection

## Author
Prem Vikas  
MSc Data Science and Analytics, Munster Technological University

## Files
- `thesis/Segmentation_Model_for_Brain_Tumor_Using_MRI.pdf` - Full thesis report
- `notebooks/` - Training and evaluation code (optional)
- `data/` - Sample MRI images and masks (optional)
- `images/` - ROC curves, segmented examples, evaluation plots

---
