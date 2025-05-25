## DeepFake Detection: US Elections

PAPER (viewable): https://www.overleaf.com/read/yqsghgnvfwcc#7a6509


A final year project focused on detecting DeepFake media in the context of the 2024 US Presidential Elections using novel preprocessing techniques and deep learning strategies.


**Overview**

DeepFake media has become an influential tool in spreading misinformation, particularly in political contexts. This project addresses the rising threat of DeepFake manipulation in political campaigns by building a robust detection system with advanced preprocessing and model training.


**Objectives**

- Analyze and preprocess DeepFake datasets for better generalization.

- Detect spatial and temporal facial artifacts using advanced techniques (CNN, RNN/LSTM, Transformers, Optical Flow).

- Evaluate the system on real-world data involving 2024 US Presidential candidates.

- Contribute to peace, justice, and responsible media consumption during electoral periods.


**Key Features**

- Preprocessing Techniques: Sampling, Data Augmentation, Noise Detection, Pixel Normalization, Image Compression.

- Artifact Detection: Spatial and Temporal artifacts through deep learning.

- Model Architectures: ResNet50, Autoencoders, Transformer-based modules.

- Evaluation Metrics: Confusion Matrix, ROC/AUC, Cross-Entropy Loss.


**Dataset**

The system utilizes multiple public DeepFake datasets with an added focus on:

- FaceForensics++

- Celeb-DF

- UADFV


**Tech Stack**
- Python

- PyTorch / TensorFlow

- OpenCV

- Scikit-learn

- Matplotlib / Seaborn

- Streamlit (for frontend integration)


**Results Summary**

| Metric              | Value  |
| ------------------- | ------ |
| Train Accuracy      | \~94%  |
| Validation Accuracy | \~91%  |
| AUC (avg)           | \~0.92 |


**Project Structure**
.
├── code-folder/                 

├── datasets/               

├── metrics/        

├── models/           

├── app/                  

└── README.md


**Future Work**
- Expand audio DeepFake detection integration.

- Real-time video verification tool.

- Enhance robustness for low-quality or compressed videos.

- Deploy as a browser plugin or mobile application.


**Contributors**
- Eesha Tariq (21L-6269)

- AbdurRehman Haroon (21L-5691)

- Javeria Shahid (21L-7694)

Supervised by: Dr. Asma Ahmad Farhan

National University of Computer and Emerging Sciences, Lahore


**License**

This project is intended for educational and research use only. Please cite appropriately.
