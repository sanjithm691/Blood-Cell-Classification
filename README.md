# 🩸 Decoding Cellular Complexity: A Deep Learning Expedition in Blood Cell Image Classification

## 🔍 **Project Overview**
This project introduces an advanced framework for blood cell image classification, leveraging cutting-edge deep learning techniques to enhance diagnostic accuracy. Using a meticulously curated dataset, the hybrid InceptionV3-Xception model achieved a remarkable test accuracy of 98.51%, setting a benchmark in medical diagnostics.

## 🌟 **Key Features**
- **Dataset:**  
  - 17,092 high-resolution blood cell images sourced from the Hospital Clinic of Barcelona.  
  - Expert annotations by clinical pathologists ensure data quality.

- **Deep Learning Models:**  
  - Convolutional Neural Networks (CNNs), U-Net, ResNet-50, VGG-16, DenseNet-201, MobileNet-V2.  
  - Supervised Contrastive Learning for enhanced feature extraction.
  - InceptionV3 and Xception
  - Hybrid Model combining InceptionV3 and Xception architectures.

- **Performance Highlights:**  
  - **Hybrid Model:** Test accuracy of 98.51%, showcasing exceptional classification performance.  
  - **Xception Model:** Test accuracy of 97.89%.  
  - **Supervised Contrastive Learning:** Test accuracy of 96.35%.  
  - Robust evaluations performed with data shuffling and cross-validation.

- **Applications:**  
  - Automated blood cell classification for improved diagnostics.  
  - Early detection of diseases like leukemia, autoimmune disorders, and other hematologic conditions.  

## 🛠️ **Methodology**
1. **Data Preprocessing:**  
   - Standardized image dimensions to 224x224 pixels.  
   - Class-stratified data splits (70% training, 30% testing).  
   - Applied SMOTE to address class imbalance.

2. **Model Training:**  
   - Transfer learning with pre-trained architectures and customized classification layers.  
   - Optimization using Adam, RMSprop, and SGD optimizers.

3. **Evaluation:**  
   - Metrics include accuracy, precision, recall, F1-score, and confusion matrices.  
   - Comparative analysis across architectures, with and without data shuffling.

## 📊 **Results**
Top-performing models based on test accuracy:

| **Model**                      | **Train Accuracy** | **Test Accuracy** |
|---------------------------------|--------------------|-------------------|
| Hybrid (InceptionV3 + Xception)| 99.75%            | 98.51%           |
| Xception                        | 99.34%            | 97.89%           |
| Supervised Contrastive Learning | 98.39%            | 96.35%           |

## 🧪 **Conclusion**
This project demonstrates the potential of hybrid deep learning models to revolutionize blood cell image classification, achieving high diagnostic accuracy and reliability. Robust preprocessing and model evaluation strategies were pivotal in attaining these results, offering valuable insights for real-world medical applications.

## 🚀 **Future Work**
- Investigate additional deep learning architectures and hybrid models.  
- Expand the study to more diverse datasets.  
- Integrate the framework with real-time diagnostic tools for clinical deployment.


Deep learning not only enhances diagnostic precision but also accelerates the process, enabling timely interventions that can save lives and redefine medical imaging practices.
