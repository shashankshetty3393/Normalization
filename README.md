Normalization in Data Processing
Normalization is the process of rescaling data to a specific range, usually [0,1] or [-1,1]. It ensures that all features contribute equally to a model and helps in improving model convergence.
Why Normalization?
Ensures Uniform Scale: Brings all features into the same range, making the model less sensitive to varying feature scales.
Improves Gradient Descent Performance: Helps models converge faster by keeping values within a small, consistent range.
Used for Distance-Based Models: Essential for algorithms like KNN, K-means, and Neural Networks, which rely on distance calculations.
When to Use Normalization?
When features have different units or scales.
When using models that require data within a specific range (e.g., deep learning).
When working with datasets containing outliers, since Min-Max scaling is sensitive to extreme values.
When Not to Use Normalization?
When data follows a Gaussian distribution (use Standardization instead).
When working with tree-based models (e.g., Decision Trees, Random Forest) that do not require feature scaling.
