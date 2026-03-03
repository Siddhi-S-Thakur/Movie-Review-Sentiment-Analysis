# Movie Review Sentiment Analysis (ML vs DL Comparison)

## Project Overview
This project performs Sentiment Analysis on movie reviews using both Machine Learning (ML) and Deep Learning (DL) models.

The goal is to classify reviews as:
- Positive 😊
- Negative 😞

The project compares traditional ML algorithms with a Deep Learning Neural Network to determine which approach performs best.


## Dataset
- Dataset: IMDb Movie Reviews Dataset
- Total Reviews: 50,000
- Balanced dataset (Positive & Negative)


## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow / Keras


## Data Preprocessing
- Removed special characters
- Converted text to lowercase
- Removed stopwords
- TF-IDF Vectorization (for ML models)
- Tokenization & Padding (for DL model)
- Train-Test Split (80-20)


## Machine Learning Models Used
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. XGBoost
5. K-Nearest Neighbors (KNN)
6. Support Vector Machine (SVM)


## Deep Learning Model
- Sequential Neural Network
- Embedding Layer
- Dense Layers
- Sigmoid Activation for Binary Classification


## Model Evaluation
Models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Loss (for DL model)
- Matplotlib Visualization for comparison


## Results
The performance of ML and DL models was compared using a bar graph visualization.

The best-performing model achieved the highest accuracy on the test dataset.


## Conclusion
This project demonstrates the comparison between traditional Machine Learning algorithms and Deep Learning models for text classification tasks.

It highlights:
- How feature engineering impacts ML performance
- How sequence modeling benefits Deep Learning
- Practical implementation of NLP pipelines


## Author
Siddhi Thakur
