# Dog Breed Classification using CNN 🐶

### 📚 **Overview**
This project implements a **Convolutional Neural Network (CNN)** to accurately classify dog breeds from images. Leveraging state-of-the-art feature extractors like **ResNet50V2**, **DenseNet121**, and **NASNetMobile**, the system achieves a high classification accuracy, providing a robust and efficient solution to dog breed identification.

---

### 🚀 **Features**
- **High Accuracy**: Achieved 96.67% training accuracy and 83% validation accuracy by combining multiple feature extractors.  
- **User-Friendly Interface**: Designed for seamless predictions.  
- **Robust Training Techniques**: Addressed class imbalances and optimized hyperparameters for superior performance.  
- **Transfer Learning**: Leveraged pre-trained models for better accuracy and efficiency.  

---

### 🛠 **Technologies Used**
- **Deep Learning Frameworks**: TensorFlow, Keras  
- **Programming Language**: Python  
- **Development Tools**: JupyterLab, OpenCV, Pandas  
- **Dataset**: Stanford Dogs Dataset (20,000+ images, 120 breeds)  

---

### 📊 **Results**
- Comparison of model performance over 20 epochs:

  | Model            | Loss   | Accuracy |
  |-------------------|--------|----------|
  | ResNet50V2       | 0.4476 | 85.84%   |
  | DenseNet121      | 0.3873 | 86.53%   |
  | NASNetMobile     | 0.4657 | 83.91%   |
  
- **Combined Architecture**: 96.67% training accuracy after 60 epochs.

---

### 📝 **Key Objectives**
- Assemble a diverse dataset of dog breeds.  
- Optimize CNN architecture for breed identification.  
- Implement techniques to address class imbalances.  
- Develop a user-friendly application interface.  
- Share documentation to foster research and practical applications.  

---

### ⚙️ **System Design & Methodology**
1. **Dataset Curation**: Used Stanford Dogs Dataset for training and validation.  
2. **Model Architecture**: Combined ResNet50V2, DenseNet121, and NASNetMobile to extract features.  
3. **Training Process**: Fine-tuned hyperparameters using Adam optimizer and categorical cross-entropy loss.  
4. **Evaluation**: Metrics like accuracy, precision, recall, and F1 score were used for performance evaluation.  

---

### 🔮 **Future Work**
- Expand the model to include additional breeds.  
- Integrate real-time image detection for live predictions.  
- Optimize for mobile deployment to enable on-the-go breed identification.  

---

### 📂 **Project Structure**
- **data/**: Dataset and preprocessing scripts.  
- **models/**: Saved models and training configurations.  
- **notebooks/**: Jupyter notebooks for training and analysis.  
- **app/**: Code for the user interface and deployment.

---

### 🤝 **Contributions**
This project is open for collaboration. Feel free to fork the repository, raise issues, or submit pull requests.
