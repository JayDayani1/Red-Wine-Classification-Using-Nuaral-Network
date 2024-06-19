# Red-Wine-Classification-Using-Nuaral-Network
This repository contains the Jupyter Notebook for classifying red wine quality using a neural network. The project demonstrates the use of deep learning techniques to predict the quality of red wine based on its physicochemical properties.

## Project Description

### Objective

The objective of this project is to build and evaluate a neural network model to classify the quality of red wine. The key tasks include:

1. **Data Preprocessing**: Cleaning and preparing the data for analysis.
2. **Feature Selection**: Selecting relevant features for the model.
3. **Model Building**: Constructing and training a neural network model.
4. **Evaluation**: Assessing the performance of the model using appropriate metrics.

## File Description

- **Red Wine Classification Using Neural Network.ipynb**: This is the main Jupyter Notebook file containing all the code, visualizations, and explanations for the project tasks.

## Requirements

To run the notebook, you will need the following Python packages:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `tensorflow`
- `scikit-learn`
- `jupyter`

**Observation:**
The TF Estimator DNN Classifier and the Neural Network using TF.Keras produced consistent results, with both models achieving similar accuracies of approximately 0.72 on the test dataset. The training process involved 20 epochs, resulting in improved training accuracies from 0.69 to 0.72 and training losses from 0.55 to 0.55. The validation set showed slightly lower accuracies of around 0.68 and a validation loss of 0.61, suggesting a moderate level of performance. However, warnings regarding deprecated functions and discrepancies between training and validation metrics indicate areas for potential improvement. Further refinement and evaluation, including the use of updated TensorFlow functions, are advised for optimal performance and generalization of the models.

**Conclusion**
The model's performance is consistent across both implementations, with accuracies ranging from 0.7156 to 0.7189 on the test dataset. However, warnings about deprecated TensorFlow functions and discrepancies in training and validation accuracies suggest areas for improvement. Updating the code to use recommended functions (e.g., tf.keras) and further analysis, including additional evaluation metrics and model comparisons, is recommended. Further refinement and evaluation are needed for optimal performance and generalization.
