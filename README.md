# Design & Evaluation of a Low-Latency and Attack-Intensity-Robust DDoS Detection System (P72) 
## Team and Client
Client: Gavin Zhao
Supervisor: Mee Loong (Bobby) Yang 
Team members: Charles Thaugland, Brenna Yan, Tatenda Chataira, Evan Hewett

# Scope Overview
## Functional requirements 

    Models will process CIC-DDoS2019 Datasets 

    System shall extract the data and form 7 core window level features 

    System shall extract the data and form an extra optional 3 window level features 

    Machine learning models will utilize the linear regression and random forest algorithms 

    The trained machine learning model should perform binary classification by classifying network traffic into either normal or DDoS 

    A structured report will be produced, evaluating and comparing the performance of the models. 

## Non-Functional Requirements 

    System shall perform with low false positives and high accuracy, detection should be low latency 

    Robust system throughout different window sizes 

    The evaluation and testing of models should be accurate, using standard metrics 

    Models developed shall follow core development principles: 

    Usability, Scalability, Maintainability, Portability and Security 

# Deliverables
    Clean and processed datasets 

    Explanatory Data Analysis (EDA) Report 

    Trained linear regression and random forest machine learning models 

    Model classification performance results (F1-score, recall, precision, FPR) 

    Timeless evaluation (time-to-detect) 

    System robustness analysis across attack intensities 

    Final DDoS detection system prototype 
