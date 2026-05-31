🌿 Plant Disease Lesion Segmentation and Severity Estimation using U-Net

This project presents a deep learning–based framework for automatic plant disease lesion segmentation and disease severity estimation using a custom U-Net architecture implemented in PyTorch. The model was trained on a leaf disease dataset containing approximately 3,528 annotated images along with corresponding lesion masks.

The proposed system effectively learns the spatial and morphological characteristics of diseased leaf regions and delivers accurate segmentation results for various plant disease patterns. To improve robustness and reduce overfitting, multiple data augmentation techniques were applied, including image flipping, rotation, brightness adjustment, and scaling.

The framework utilizes a hybrid loss function combining Tversky Loss and Binary Cross Entropy (BCE) Loss, which significantly improves segmentation performance for small, irregular, and imbalanced lesion regions.

🚀 Key Features
Automatic plant disease lesion segmentation
Disease severity estimation based on infected area
Custom U-Net architecture in PyTorch
Advanced augmentation pipeline for better generalization
Hybrid Tversky + BCE Loss for precise segmentation
Heatmap and mask visualization support
Supports training, evaluation, and inference workflows
📊 Model Performance

The trained model achieved strong segmentation performance with:

High lesion detection accuracy
Improved boundary localization
Better handling of small and complex disease spots
Reliable disease severity estimation from segmented regions
🛠️ Technologies Used
Python
PyTorch
OpenCV
NumPy
Matplotlib
Albumentations
📂 Project Workflow
Dataset preprocessing and annotation handling
Data augmentation and normalization
U-Net model training
Lesion mask prediction
Disease severity calculation
Visualization and evaluation
🌱 Applications
Smart agriculture
Precision farming
Early plant disease detection
Automated crop monitoring
Agricultural AI systems
🔮 Future Improvements
Multi-class disease segmentation
Real-time mobile deployment
Edge AI integration for IoT devices
Transformer-based segmentation models
Cloud-based agricultural monitoring dashboard
📌 Conclusion

This project demonstrates the effectiveness of deep learning techniques for automated plant disease analysis. The proposed U-Net–based framework provides accurate lesion segmentation and reliable disease severity estimation, making it a valuable solution for intelligent agricultural monitoring and precision farming applications.
