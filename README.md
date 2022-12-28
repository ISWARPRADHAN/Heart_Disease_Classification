# <div align="center">Heart Disease Classification using Machine Learning</div>
<div align="center"><img src="https://github.com/ISWARPRADHAN/Heart_Disease_Classification/blob/main/intro.gif?raw=true" width="80%"></div>
                                   

## Overview:
WHO announced that cardiovascular diseases is the top one killer over the world. There are seventeen million people died from it every year, especially heart disease. Prevention is better than cure. If we can evaluate the risk of every patient who probably has heart disease, that is, not only patients but also everyone can do something earlier to keep illness away.

## Dataset:
[Heart Disease UCI](https://www.kaggle.com/ronitf/heart-disease-uci)
#### Dataset attributes:
There are thirteen features and one target as below:

- age: The person's age in years
- sex: The person's sex (1 = male, 0 = female)
- cp: The chest pain experienced (Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic)
- trestbps: The person's resting blood pressure (mm Hg on admission to the hospital)
- chol: The person's cholesterol measurement in mg/dl
- fbs: The person's fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)
- restecg: Resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria)
- thalach: The person's maximum heart rate achieved
- exang: Exercise induced angina (1 = yes; 0 = no)
- oldpeak: ST depression induced by exercise relative to rest
- slope: the slope of the peak exercise ST segment (Value 1: upsloping, Value 2: flat, Value 3: downsloping)
- ca: The number of major vessels (0-3)
- thal: A blood disorder called thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect)

- target: Heart disease (0 = no, 1 = yes)
## Implementation:

**Libraries:**  `NumPy` `pandas` `matplotlib` `sklearn` `seaborn`
## Data Exploration:
<img src="https://github.com/ISWARPRADHAN/Heart_Disease_Classification/blob/main/output/eda1.PNG?raw=true" width="40%"> <img src="https://github.com/ISWARPRADHAN/Heart_Disease_Classification/blob/main/output/eda2.PNG?raw=true" width="40%">

### Heart disease frequency w.r.t. Age:
<img src ="https://github.com/ISWARPRADHAN/Heart_Disease_Classification/blob/main/output/eda3.PNG?raw=true">
<img src = "https://github.com/ISWARPRADHAN/Heart_Disease_Classification/blob/main/output/eda4.PNG?raw=true" width="80%">
<img src="https://github.com/ISWARPRADHAN/Heart_Disease_Classification/blob/main/output/eda5.PNG?raw=true">

### Heart disease frequency w.r.t. Slope:
<img src= "https://github.com/ISWARPRADHAN/Heart_Disease_Classification/blob/main/output/eda6.PNG?raw=true" width="80%">

### Heart disease frequency w.r.t. FBS:
<img src="https://github.com/ISWARPRADHAN/Heart_Disease_Classification/blob/main/output/fbs.PNG?raw=true" width="80%">

## Heart disease frequency w.r.t. Chest pain type:
<img src="https://github.com/ISWARPRADHAN/Heart_Disease_Classification/blob/main/output/pain.PNG?raw=true" width="80%"><br>

## Model training, Evaluations, and Predictions:
<img src="https://github.com/ISWARPRADHAN/Heart_Disease_Classification/blob/main/output/acc.PNG?raw=true" width="80%">
<br>
Our models work fine but best of them are KNN and Random Forest with 88.52% of accuracy. Let's look their confusion matrixes.

#### Confusion matrices:
<img src="https://github.com/ISWARPRADHAN/Heart_Disease_Classification/blob/main/output/CM.PNG?raw=true" width="70%">

Heart_Disease_Classification
### Learnings:
`Feature endineering`
`Feature Scaling`
`Classification Models`
`Model Evaluation`



### Feedback

If you have any feedback, please reach out at iswar.pradhan@yahoo.com


### About Me
#### Hi, I'm Iswar Pradhan! 




[1]: https://github.com/ISWARPRADHAN


