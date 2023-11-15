## COVID-19 X-Ray Classification

This GitHub repository focuses on building a Convolutional Neural Network (CNN) for classifying X-ray images as COVID-19 positive or negative. The code utilizes the dataset from [Kaggle](https://www.kaggle.com/datasets/ahemateja19bec1025/covid-xray-dataset) and achieves an impressive test accuracy of 96.45%.

### Key Steps:

1. **Dataset Exploration:**
   - The script navigates and organizes the X-ray images located in the '.\\DATA' directory.
   - Differentiates between 'covid' and 'non-covid' categories.

2. **Data Preprocessing:**
   - Resizes images to (224,224) pixels and normalizes pixel values to a scale of [0,1].
   - Converts image data and corresponding labels into numpy arrays.

3. **Model Architecture:**
   - Constructs a CNN using TensorFlow and Keras.
   - Employs convolutional layers with max pooling, followed by fully connected layers.
   - Utilizes the binary cross-entropy loss function and the Adam optimizer during training.

4. **Training and Evaluation:**
   - Splits the dataset into training, validation, and test sets using `train_test_split`.
   - Implements early stopping to prevent overfitting.
   - Achieves a remarkable test accuracy of 96.45%.

5. **Performance Metrics:**
   - Generates a classification report and a confusion matrix for a comprehensive evaluation.

6. **Model Visualization:**
   - Utilizes `plot_model` to create a visual representation of the CNN architecture.
   - Displays the model summary and its weights.

7. **Model Saving:**
   - Saves the trained model in the Hierarchical Data Format (HDF5) as 'my_model.h5'.

Feel free to explore and adapt the code for your own projects. For further details, refer to the script and the model plot ('model_plot.png') generated in the repository. Achieving a high test accuracy demonstrates the effectiveness of the model in distinguishing COVID-19 cases from X-ray images.
