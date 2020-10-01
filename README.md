# Transportation Mode Detection
This repository includes transportation mode detection with unconstrained smartphones sensors
using various Machine learning algorithms.
## Dataset
Dataset is based on the thirteen users who collected the data during their daily activities. 
The dataset includes all sensors available in phones and distinguishes five transportation modes: 
being on a ***car***, on a ***bus***, on a ***train***, standing ***still*** and ***walking***.

Sensors included in the dataset are:
* Accelerometer
* Sound
* Orientation
* Linear acceleration
* Speed
* Gyroscope
* Rotation vector
* Game rotation vector
* Gyroscope uncalibrated

Dataset link  https://www.kaggle.com/fschwartzer/tmd-dataset-5-seconds-sliding-window

## Model Training
The following classification models are used:
* Random Forest
* lightGBM
* Gradient Boosting Classifier
* KNN
* Naivye Bayes
* SVC
* xgboost

## Results
| Model | Accuracy |
| ----- | -------- |
| Random Forest | 0.945 |
| lightGBM | 0.851 |
| Gradient Boosting Classifier | 0.963 |
| KNN | 0.821 |
| Naivye Bayes | 0.586 |
| SVC | 0.745 |
| xgboost | 0.973 |

## Conclusion
Out of all the algorithms used, xgboost gives the best accuracy of 0.9737.

Good Luck!
