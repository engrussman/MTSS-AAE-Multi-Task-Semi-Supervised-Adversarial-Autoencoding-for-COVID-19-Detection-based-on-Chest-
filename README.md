
# MTSS AAE Multi Task Semi Supervised Adversarial Autoencoding for COVID-19 Detection based on Chest XRay Images

Efficient diagnosis of COVID-19 plays an important role in preventing the spread of the disease. There are three major modalities to diagnose COVID-19 which include polymerase chain reaction tests, computed tomography scans, and chest X-rays (CXRs). Among these, diagnosis using CXRs is the most economical approach; however, it required extensive human expertise to diagnose COVID-19 in CXRs, which may deprive it of cost-effectiveness. The computer-aided diagnosis with deep learning have the potential to perform accurate detection of COVID-19 in CXRs without human intervention while preserving its cost-effectiveness. Many efforts have been made to develop a highly accurate and robust solution. However, due to the limited amount of labeled data, existing solutions are evaluated on a small set of test dataset. In this work, we proposed a solution to this problem by using a multi-task semi-supervised learning (MTSSL) framework that utilized auxiliary tasks for which adequate data is publicly available. Specifically, we utilized Pneumonia, Lung Opacity, and Pleural Effusion as additional tasks using the ChesXpert dataset. We illustrated that the primary task of COVID-19 detection, for which only limited labeled data is available, can be improved by using this additional data. We further employed an adversarial autoencoder (AAE), which has a strong capability to learn powerful and discriminative features, within our MTSSL framework to maximize the benefit of multi-task learning. In addition, the supervised classification networks in combination with the unsupervised AAE empower semi-supervised learning, which includes a discriminative part in the unsupervised AAE training pipeline. The generalization of our framework is improved due to this semi-supervised learning and thus it leads to enhancement in COVID-19 detection performance. The proposed model is \textcolor{red}{rigorously} evaluated on the largest publicly available COVID-19 dataset and experimental results show that the proposed model attained state-of-the-art performance.

## Pipeline
Model diagram is shown in the figure:

![Model Diagram](https://github.com/engrussman/Multi-Task-Semi-Supervised-Adversarial-Autoencoding-for-COVID-19-Detection-based-on-Chest-Xray-image/blob/main/Images/Model%20Diagram.png)

## Dataset:

Multiple datasets are used for the research. These datasets are listed below:

 1. [RSNA Pneumonia Detection Challenge Dataset](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/data)
 2. **[Covid  Chestxray-dataset](https://github.com/ieee8023/covid-chestxray-dataset)**
 3. **[ Figure1 COVID Chestxray dataset Initiative](https://github.com/agchung/Figure1-COVID-chestxray-dataset)**

## Results:
Following are the results of our proposed solution in comparison with other methods:
![enter image description here](https://github.com/engrussman/Multi-Task-Semi-Supervised-Adversarial-Autoencoding-for-COVID-19-Detection-based-on-Chest-Xray-image/blob/main/Images/Results.png)

#### Confusion Matrix:
![enter image description here](https://github.com/engrussman/Multi-Task-Semi-Supervised-Adversarial-Autoencoding-for-COVID-19-Detection-based-on-Chest-Xray-image/blob/main/Images/CF.png)
