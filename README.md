A Deep Learning model utilizing a custom Sequential Convolutional Neural Network (CNN) to classify medical X-ray images into COVID-19 and Normal categories with a clinical interpretation layer.

Dataset Scale: Processed and managed a medical imaging dataset of 13,808 files, strategically partitioned into training (11,047 images) and validation (2,761 images) subsets.

Model Architecture: Developed a 5-layer Sequential CNN featuring:

Multiple Convolutional Layers: Utilized 32, 64, and 124 filters with ReLU activation for hierarchical feature extraction.

Regularization Strategy: Integrated Dropout layers (ranging from 0.25 to 0.5) to mitigate overfitting and enhance model generalization on unseen medical data.

Dense Classification: A 512-unit fully connected layer followed by a Sigmoid output for binary classification.

Clinical Logic Layer: Uniquely integrated a clinical_interpretation function that maps raw model probabilities to diagnostic recommendations (e.g., classifying results as "High Likelihood" and recommending PCR confirmatory tests for scores >80%).
