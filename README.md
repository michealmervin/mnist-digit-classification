## MNIST Digit Classification

### Problem Statement
- Build a machine learning pipeline to classify handwritten digits (0–9)
- Input: Image of a digit
- Output: Predicted numerical digit

### Dataset
- MNIST handwritten digit dataset
- 60,000 training images
- 10,000 testing images
- Each image is 28×28 grayscale

### Data Preprocessing
- Pixel values normalized to range [0,1]
- Images flattened from 28×28 to 784 features

### Model Architecture
- Fully connected neural network
- One hidden layer with ReLU activation
- Output layer with Softmax activation

### Training
- Optimizer: Adam
- Loss: Sparse Categorical Crossentropy
- Epochs: 5

### Evaluation
- Test accuracy achieved: ~97.57%
- Model performs well on unseen data

### Prediction Pipeline
- Accepts an image as input
- Processes and predicts the digit
- Outputs numerical class (0–9)

### Tools Used
- Python
- TensorFlow / Keras
- NumPy
- Google Colab

### Conclusion
- The model successfully classifies handwritten digits
- Demonstrates an end-to-end ML pipeline
