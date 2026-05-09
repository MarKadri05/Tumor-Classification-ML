# Brain Tumor Classification | Deep Learning & Transfer Learning

This project implements a high-performance medical image classification system to identify four types of brain conditions: Glioma, Meningioma, Pituitary tumor, and No Tumor.

## Project Overview
The model was developed using a deep learning pipeline to automate the detection process in medical resonance imaging (MRI). It leverages the power of **Transfer Learning** to achieve professional-grade results with optimized training time.

## Technical Stack
* **Language:** Python
* **Frameworks:** TensorFlow / Keras
* **Architecture:** DenseNet121 (Pre-trained on ImageNet)
* **Key Libraries:** NumPy, Pandas, OpenCV, Matplotlib, Scikit-learn
* **Environment:** Kaggle Notebooks (GPU accelerated)

## Model Implementation
* **Feature Extraction:** Used DenseNet121 as a base model, freezing early layers to retain generic image features.
* **Global Average Pooling:** Integrated to reduce spatial dimensions and prevent overfitting.
* **Optimization:** Implemented the **Adam Optimizer** and Categorical Crossentropy loss function.
* **Hyperparameters:** Trained for 20 epochs with a Batch Size of 32.

## Results
* **Accuracy:** Achieved a peak validation accuracy of **95%**.
* **Robustness:** The model shows consistent performance across all four classes, as evidenced by the confusion matrix and classification reports included in the notebook.

## License
This project is licensed under the **MIT License**.
