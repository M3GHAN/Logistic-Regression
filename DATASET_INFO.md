# Dataset Information

## Titanic Dataset

The Titanic dataset used in this project is available through the `scikit-learn` library. It contains data on passengers aboard the Titanic, including features such as age, sex, passenger class, and survival status. 

### How to Download the Dataset

You can download the Titanic dataset directly from the `scikit-learn` library using the following code snippet:

```python
from sklearn.datasets import fetch_openml

# Load the Titanic dataset
titanic = fetch_openml(name='titanic', version=1, as_frame=True)
df = titanic['data']
df['survived'] = titanic['target']
