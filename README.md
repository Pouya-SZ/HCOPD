# HCOPD
Classification of Saliva Samples of Healthy Control (HC) and COPD -- HCOPD 

This repository introduces a novel dataset for the classification of Chronic Obstructive Pulmonary Disease (COPD) patients and Healthy Controls. The main dataset includes demographic information on 4 groups of saliva samples (COPD-HC-Asthma-Infected) collected in the frame of the Exasens research project. Patient materials were collected by BioMaterialBank Nord (Borstel, Germany). A permittivity biosensor, developed at IHP Microelectronics (Frankfurt Oder, Germany), was used for the dielectric characterization of the saliva samples for classification purposes (https://doi.org/10.3390/healthcare7010011). 

The investigated machine learning classifiers for this dataset include: Artificial Neural Networks (ANN), Support Vector Machines (SVM), Gaussian Naive Bayes (GNB), Logistic Regression (LR), Gradient Boosting decision tree algorithm (XGBoost).    

Attribute Information: 

1- Diagnosis (COPD-HC-Asthma-Infected) 

2- ID 

3- Age

4- Gender (1=male, 0=female) 

5- Smoking Status (1=Non-smoker, 2=Ex-smoker, 3=Active-smoker) 

6- Saliva Permittivity:

    a) Imaginary part (Min(Δ)=Absolute minumum value, Avg.(Δ)=Average)  
    
    b) Real part (Min(Δ)=Absolute minumum value, Avg.(Δ)=Average) 
    
To use the introduced dataset please cite the following papers: 
- P. S. Zarrin, N. Roeckendorf, and C. Wenger. In-vitro Classification of Saliva Samples of COPD Patients and Healthy Control Using Non-perceptron-based Machine Learning Tools. Annals of biomedical engineering, 2020. 

- Soltani Zarrin, P.; Ibne Jamal, F.; Roeckendorf, N.; Wenger, C. Development of a Portable Dielectric Biosensor for Rapid Detection of Viscosity Variations and Its In Vitro Evaluations Using Saliva Samples of COPD Patients and Healthy Control. Healthcare 2019, 7, 11.

- Soltani Zarrin, P.; Jamal, F.I.; Guha, S.; Wessel, J.; Kissinger, D.; Wenger, C. Design and Fabrication of a BiCMOS Dielectric Sensor for Viscosity Measurements: A Possible Solution for Early Detection of COPD. Biosensors 2018, 8, 78.

- P.S. Zarrin and C. Wenger. Pattern Recognition for COPD Diagnostics Using an Artificial Neural Network and Its Potential Integration on Hardware-based Neuromorphic Platforms. Springer Lecture Notes in Computer Science (LNCS), Vol. 11731, pp. 284-288, 2019.   

- Krause, T., Ramaker, K., Röckendorf, N., Sinnecker, H. and Frey, A., 2016. Airway mucins–suitable biomarkers to predict an upcoming exacerbation in COPD and asthma?. Pneumologie, 70(07), p.P43.
