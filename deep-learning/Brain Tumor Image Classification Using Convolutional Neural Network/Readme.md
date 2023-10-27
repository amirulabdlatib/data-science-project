
# Brain Tumor Classification Using Deep Learning

## Overview

This project aims to classify brain tumor images into four categories: glioma tumor, meningioma tumor, normal, and pituitary tumor using deep learning techniques. The dataset has been enhanced to ensure data consistency and quality. The classification model is built using TensorFlow/Keras and evaluated for accuracy.

## Data

- The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/thomasdubail/brain-tumors-256x256?rvi=1).
- Enhancements made: Removal of redundant data, image normalization, resizing to a consistent 256x256-pixel size.
- Data is organized into four categories: glioma tumor, meningioma tumor, normal, and pituitary tumor.

## Model

- Deep learning model architecture with convolutional and fully connected layers.
- Model compiled with Adam optimizer and sparse categorical cross-entropy loss function.
- Training and evaluation on a split dataset, with an emphasis on test set performance.

## Results

- Training accuracy: Approximately 97.58%.
- Test accuracy: Approximately 72.58%.
- Potential for improvement through techniques like data augmentation, model architecture adjustments, and hyperparameter tuning.

## Evaluation

- Confusion matrix and classification report used for model evaluation.
- Visualization of the confusion matrix for a better understanding of the classification results.

## Usage

- Clone the repository and follow the Jupyter Notebook or Python script for detailed implementation.
- Experiment with different deep learning architectures and hyperparameters to improve model performance.

## License

- This dataset is released under the CC0 license, promoting collaboration and innovation in the medical research community.

## Acknowledgments

- Original data source and authors' contributions acknowledged.
