## Vehicle Damage Insurance Claim Verification

This project uses a CNN model to classify vehicle damages into six categories:
- Crack
- Scratch
- Tire Flat
- Dent
- Glass Shatter
- Lamp Broken

### Model:
- 5-layer Conv2D CNN
- ReLU activation, Batch Normalization, Global Average Pooling
- Regularization: Dropout, Data Augmentation
- Class Imbalance handling: Class Weights

### Instructions:
1. Extract `data.zip` (contains images and CSV) to the `/data` folder.
2. Run the notebook `Insurance Claim Verification.ipynb`.

### Results:
The model achieved a strong AUC of 0.94 and precision of 0.72, demonstrating its effectiveness in differentiating between vehicle damage categories.

### Notes:
- Images in the `data.zip` should be placed in the `/data` folder for the model to train correctly.
