Fraud Detection in Healthcare using Machine Learning

 Overview
This repository contains a research-based academic project** focused on detecting healthcare fraud using **Machine Learning techniques.  
The study reviews existing fraud detection methods and proposes a hybrid ML approach** combining **Local Outlier Factor (LOF) and Random Forest to improve detection accuracy and reduce false positives.

 Project Information
- Project Type: Research Paper  
- Institution: Bennett University (Times of India Group)  
- Authors: Harshita Jain, Aryan Singh  
- Domain: Data Science / Healthcare Analytics  
- Keywords: Machine Learning, Fraud Detection, LOF, Random Forest, Healthcare  

Problem Statement
Healthcare insurance fraud leads to significant financial losses and is difficult to detect due to:
- Large-scale, high-dimensional claim data  
- Complex provider–patient relationships  
- Presence of subtle and evolving fraud patterns  

Traditional rule-based systems struggle with scalability and accuracy, motivating the use of machine learning approaches.

 Proposed Approach
This research proposes a **hybrid fraud detection framework**:

1. Anomaly Detection
   - Apply **Local Outlier Factor (LOF)** to identify suspicious and abnormal healthcare claims.

2. **Classification**
   - Use **Random Forest** to classify detected anomalies as fraudulent or non-fraudulent.

3. **Outcome**
   - Improved precision
   - Reduced false positives
   - Better suitability for near real-time fraud detection

## Abstract
Healthcare fraud detection is a major challenge due to the complexity and scale of insurance data.  
This study reviews multiple machine learning and data mining approaches and proposes a hybrid model combining **Local Outlier Factor (LOF)** for anomaly detection and **Random Forest** for classification.  
The approach enhances fraud detection accuracy while reducing false positives, making it suitable for real-world healthcare analytics systems.

Repository Contents
| File | Description |
|------|-------------|
| `data_science_project_new.pdf` | Full research paper including methodology, algorithms, and analysis |
| (future) `notebook_template.ipynb` | Planned Python implementation of the proposed model |

Future Scope
- Implement LOF + Random Forest pipeline in Python  
- Evaluate performance on real healthcare claims datasets  
- Optimize model for scalable and real-time fraud detection  

 Citation
If you use or reference this work, please cite:

> Harshita Jain, Aryan Singh.  
> "Fraud Detection in Healthcare Based on Machine Learning",  
> Bennett University, 2025.
