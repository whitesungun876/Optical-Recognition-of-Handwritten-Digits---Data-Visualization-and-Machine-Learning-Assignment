Overview

This project focuses on using data visualization and machine learning to predict handwritten digits from the Optical Recognition of Handwritten Digits Dataset. The dataset contains grayscale images of digits (0-9), with features extracted as 8x8 pixel grids.

The project includes baseline model evaluation and a Logistic Regression implementation to compare performance.

Key Features

Data Exploration and Visualization:
Visualize the digit images and their distributions.
Compute and display the average image of each digit class.

Machine Learning Models:
Train a baseline classifier using Scikit-learn's DummyClassifier.
Implement and evaluate a Logistic Regression model.

Performance Evaluation:
Use metrics such as accuracy and a classification report to assess models.
Analyze differences in model performance across digit classes.

Dataset Description
Instances: 1797
Features: 64 (8x8 pixel grids, grayscale values ranging from 0 to 16)
Classes: 10 (digits 0-9)
Source: UCI Machine Learning Repository

Exercises
1. Data Visualization
Display the first digit from the dataset.
Plot the average image for each digit (0-9) in a 5x2 grid.
2. Class Distribution
Create histograms to compare class distributions in the training and testing sets.
3. Baseline Model
Train a baseline model using Scikit-learn's DummyClassifier with appropriate strategy.
Evaluate the model using a test dataset.
4. Logistic Regression
Train a Logistic Regression model with the liblinear solver.
Compare its performance against the baseline model.
5. Insights
Analyze why Logistic Regression performs better than the baseline.
Discuss challenges in classifying certain digits, e.g., why the digit "8" may be harder to classify.
Results Summary
Baseline Model: Provides a starting point for evaluating model difficulty.
Logistic Regression: Achieves significant improvement over the baseline by leveraging patterns in the data.

Key Observations:
The Logistic Regression model handles most digits well but struggles slightly with digit "8," likely due to its similarity to other digits.

How to Run the Project

Clone this repository:
git clone https://github.com/yourusername/handwritten-digits-recognition.git
cd handwritten-digits-recognition

Install dependencies:
pip install -r requirements.txt

Follow the instructions in the notebooks folder to reproduce the results (optional).

Folder Structure
handwritten-digits-recognition/
│
├── data/                   # Dataset (not included in this repo)
├── results/                # Visualizations and evaluation reports
└── README.md               # Project documentation

Acknowledgments
Dataset by E. Alpaydin from UCI Machine Learning Repository.
Scikit-learn library for machine learning tools.




