# CodeAlpha---Iris-Flower-Classification
📌 Project Overview

This project uses the Iris dataset to classify iris flowers into three species:

    Iris-setosa

    Iris-versicolor

    Iris-virginica

Using machine learning (K-Nearest Neighbors), we predict a flower's species based on its sepal and petal measurements.
📁 Dataset

The dataset is from UCI Machine Learning Repository and contains:

    150 rows

    4 features: SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm

    1 target column: Species

🛠️ Tools & Libraries Used

    Python

    Pandas

    NumPy

    Scikit-learn

    Matplotlib

    Seaborn

🧠 Steps Performed

    Data Loading & Cleaning

        Loaded CSV using Pandas

        Removed Id column

        Checked for null values

    Feature & Target Separation

        Features: Sepal & Petal measurements

        Target: Species

    Train-Test Split

        80% training / 20% testing

        Stratified split to preserve class distribution

    Feature Scaling

        Applied StandardScaler to normalize feature values

    Model Training

        Used K-Nearest Neighbors (K=3)

        Trained on scaled training data

    Evaluation

        Achieved 100% accuracy on test set (for K=1 to 10)

        Displayed confusion matrix & classification report

        Visualized accuracy vs. k-value

        Visualized feature distribution with Seaborn pairplots

📊 Results

    Accuracy: 100%

    Best k-value range: 1–10 (no misclassification)

    Confusion Matrix showed perfect classification

📈 Visualizations Included

    Accuracy vs. k plot

    Confusion matrix heatmap

    Pairplot of features colored by species

✅ Key Concepts Learned

    Supervised learning with classification

    K-Nearest Neighbors algorithm

    Data preprocessing (scaling, splitting)

    Model evaluation techniques

    Visualization of ML performance
