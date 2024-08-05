## Graduate Admission Prediction Model Using ANN
Created an ANN to predict the likelihood of graduate school admission based on applicant features.


**Data Preprocessing:**  
- Clean and handle missing data.
- Encode categorical variables.
- Normalize numerical features.

**Model Design:**  
- *Input Layer:* Neurons equal to the number of features.
- *Hidden Layers:* One or more dense layers with ReLU activation.
- *Output Layer:* Single neuron with sigmoid activation for binary classification (admitted or not).

**Training:**  
- Split data into training and testing sets.
- Use binary cross-entropy as the loss function.
- Optimize with algorithms like Adam.
- Implement dropout to reduce overfitting.

**Evaluation:**  
- Metrics: Accuracy and precision for performance assessment.

**Tools:**  
- *Language:* Python
- *Libraries:* TensorFlow/Keras, Pandas, NumPy.
