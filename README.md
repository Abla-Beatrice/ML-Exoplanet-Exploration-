# ML-Exoplanet-Exploration

### Preprocess the Data:

  * Preprocess the dataset prior to fitting the model.
  * Perform feature selection and remove unnecessary features.
  * Use MinMaxScaler to scale the numerical data.
  * Separate the data into training and testing data.
  
### Tune Model Parameters:

  * Use GridSearch to tune model parameters.
  * Tune and compare three different classifiers (Support Vector Machine, Random Forest Classifier & Neural Network).
  
## Analysis:

* Random forests are simpler to train; it’s easier to find a good model. The complexity of a random forest grows with the number of trees in the forest, and the number of training samples we have. In SVMs, we need to do a fair amount of parameter tuning.

### Random Forest:

  |               | Before        | After       |
  |:-------------:|:-------------:|:-------------:|
  |Training Score | 0.995         | 1.0           |
  |Testing Score  | 0.883         | 0.899         |
  

  
### Support Vector Machine:

  |               | Before        | After       |
  |:-------------:|:-------------:|:-------------:|
  |Training Score | 0.837         | 0.871         |
  |Testing Score  | 0.855         | 0.883         |
  
  * Although the Random Forest model was quite successful, it would be important to train and test additional models for accuracy and reliability.
  
  ### Neural Network:
  
  * The analysis showed that Neural Network yielded an accuracy of 0.88 precision and recall of the algorithms tested.