# CA4: Flower classification

This project trains convolutional neural networks for five-class flower classification using the TensorFlow flower photos dataset.

## Contents

- `notebooks/flower_cnn_final.ipynb`: image loading, preprocessing, optimizer and learning-rate comparison, CNN training, and validation evaluation.

## Results from the final notebook

- Selected optimizer: SGD with learning rate `0.01`.
- Best validation accuracy: 73.98%.
- Final training accuracy after restoring the best weights: 74.76%.
- Final validation accuracy: 73.98%.
- Validation macro precision: 73.70%.
- Validation macro recall: 73.11%.
- Train-validation accuracy gap: 0.78 percentage points.

The original flower photos archive is large, so it is not committed. Download or place the dataset locally before running the notebook.
