# Project - DCADPCOS: 
Data-driven Computer Aided Diagnostic system for Polycystic Ovary Syndrome using Machine Learning Techniques 
## About PCOS -
PCOS is a  common hormonal disorder among women of reproductive age. Factors that might play a role include: excess insulin, low-grade inflammation, excess androgen, or it can be hereditary. The signs and symptoms of PCOS may vary woman to woman; some signs of PCOS include irregular periods, excess androgen and polycystic ovaries. 
## Diagnosis Techniques -
There is no test to definitively diagnose PCOS. Disease prediction is a challenging task in healthcare applications. However, the test requires the patient to report back to the hospital or test-centre. Often, due to inconveniences the women patients fail to visit the hospital to get the diagnostic details. Machine learning is an emerging approach that helps in the prediction, diagnosis of a disease.
## Technologies
Python
Pandas, Numpy, Sklearn, Seaborn, Matplotlib, Colab notebook, 
ML Algo's - Random Forest, Support Vector Machine, Logistic Regression & k-cross fold validation
## Methods Used
Machine Learning
Data Visualization
Predictive Modeling
etc.

Dataset - contains 43 features from 541 women, 177 of whom have PCOS. 


Input features - Age (yrs), Weight (Kg), Height(Cm), BMI,
       Blood Group, Pulse rate(bpm), RR (breaths/min), Hb(g/dl),
       Cycle(R/I), Cycle length(days), Marriage Status (Yrs),
       Pregnant(Y/N), No. of abortions, I   beta-HCG(mIU/mL),
       II    beta-HCG(mIU/mL), FSH(mIU/mL), LH(mIU/mL), FSH/LH,
       Hip(inch), Waist(inch), Waist:Hip Ratio, TSH (mIU/L),
       AMH(ng/mL), PRL(ng/mL), Vit D3 (ng/mL), PRG(ng/mL),
       RBS(mg/dl), Weight gain(Y/N), hair growth(Y/N),
       Skin darkening (Y/N), Hair loss(Y/N), Pimples(Y/N),
       Fast food (Y/N), Reg.Exercise(Y/N), BP _Systolic (mmHg),
       BP _Diastolic (mmHg), Follicle No. (L), Follicle No. (R),
       Avg. F size (L) (mm), Avg. F size (R) (mm), Endometrium (mm)

output label - 0 for non pcos & 1 for pcos patient


## System framework-
Data cleaning -> Feature Selection -> Normalization
AUC-ROC curve- 

The Receiver Operator Characteristic (ROC) curve is an evaluation metric for binary classification problems. It is a probability curve that plots the TPR against FPR at various threshold values and essentially separates the ‘signal’ from the ‘noise’. The Area Under the Curve (AUC) is the measure of the ability of a classifier to distinguish between classes and is used as a summary of the ROC curve.
When 0.5<AUC<1, there is a high chance that the classifier will be able to distinguish the positive class values from the negative class values. This is so because the classifier is able to detect more numbers of True positives and True negatives than False negatives and False positives.
ROC Scores -
0.9479166666666666 - for Random forest
0.9452030812324929 - for Logistic regression
This proves that Random Forest has a higher chance (than Logistic Regression) that the classifier will be able to distinguish the positive class values from the negative class values.
## Conclusion
RF classification approach is best for DCADPCOS
