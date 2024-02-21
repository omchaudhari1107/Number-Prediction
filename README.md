# Number-Prediction-model : 98.8% Accurate
### Must Insatll The Libarary befor use 😊
```
pip install scikit-learn
pip install matplotlib
pip install pandas
```
### Import's
```
from sklearn.datasets import load_digits
from sklearn.svm import SVC
import pandas as pd
from matplotlib import pyplot as plt
from sklearn.model_selection import train_test_split
import seaborn as sn
```
### Choose diffrent kernals for diffrent accuracy
```
model = SVC(kernel='rbf')
'linear', 'poly', 'rbf', 'sigmoid', 'precomputed'
```
### For Overfitting and Underfitting
![Screenshot 2024-02-09 174955](https://github.com/omchaudhari1107/Number-Prediction/assets/90174038/21b401fd-e141-48ca-b887-801d682c04e5)
![Screenshot 2024-02-09 175206](https://github.com/omchaudhari1107/Number-Prediction/assets/90174038/a338a800-de9d-4543-9dc3-f68d52d787b7)
