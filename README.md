# Neural-Networks-Project2
# CS5720 – Neural Networks and Deep Learning  
## Home Assignment 2 – Summer 2025

Student Id: 700765371
Student Name: Siva Kumar Choutametla

Question 1: Convolution Operations with Different Parameters

- A 5×5 input matrix and a 3×3 kernel were used to demonstrate 2D convolution.
- Four combinations were implemented using TensorFlow:
  - Stride = 1, Padding = VALID
  - Stride = 1, Padding = SAME
  - Stride = 2, Padding = VALID
  - Stride = 2, Padding = SAME
- Feature maps for each configuration were printed and analyzed.
  
Question 2: CNN Feature Extraction with Filters and Pooling
Task 1: Edge Detection using Sobel Filters
- A grayscale image was used to apply Sobel-X and Sobel-Y convolution.
- Filters:
  - Sobel X: `[-1 0 1; -2 0 2; -1 0 1]`
  - Sobel Y: `[-1 -2 -1; 0 0 0; 1 2 1]`
- The original image, Sobel-X, and Sobel-Y results were displayed using `matplotlib`.

Task 2: Max and Average Pooling
- A 4×4 random matrix was generated using NumPy.
- 2×2 Max Pooling and Average Pooling operations were applied using TensorFlow.
- The results were printed to visualize the reduction in spatial dimensions.

Question 3: Data Preprocessing – Standardization vs. Normalization

- The Iris dataset from `sklearn.datasets` was used.
- Applied:
  - **Min-Max Normalization** (values scaled to [0,1])
  - **Z-score Standardization** (mean = 0, std = 1)
- Histograms were plotted to visualize feature distributions.
- Logistic Regression was trained on:
  - Original data
  - Min-Max scaled data
  - Standardized data
- Accuracy scores were compared to observe impact of preprocessing.
