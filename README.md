# Elevate-Labs-Task-6

🌸 K-Nearest Neighbors (KNN) Classification - Iris Dataset
📌 Objective
Implement and understand K-Nearest Neighbors (KNN) algorithm for classification tasks using the classic Iris dataset. The project includes preprocessing, model training, evaluation, and decision boundary visualization.

🛠️ Tools & Libraries
Python

scikit-learn

pandas

matplotlib

numpy

📂 Dataset
Iris Dataset from sklearn.datasets. It includes 150 samples of iris flowers from three different species:

Setosa

Versicolor

Virginica

Each sample has 4 features:

Sepal length

Sepal width

Petal length

Petal width

✅ Tasks Completed
Load Dataset using sklearn.datasets.load_iris()

Normalize Features using StandardScaler

Train/Test Split using train_test_split

Train KNN Classifier using KNeighborsClassifier for different values of K

Evaluate model using:

Accuracy

Confusion Matrix

Visualize Accuracy vs K using a line plot

Plot Decision Boundaries (using first two features only for 2D visualization)

📊 Model Evaluation
Accuracy is measured for K values from 1 to 10.

Best performing K is used for final evaluation.

Confusion matrix is plotted for the best model.

Decision boundaries are visualized using a 2D plot (first two features).

📈 Output Samples
Accuracy vs K plot to find optimal K

Confusion Matrix

Decision Boundary Plot (Setosa, Versicolor, Virginica classes)

▶️ How to Run
Install required packages:

bash
Copy
Edit
pip install scikit-learn pandas matplotlib
Run the Python script in a Jupyter Notebook or any Python environment.

🧠 Key Concepts
KNN is a non-parametric, lazy learning algorithm.

It predicts the label of a new point by majority voting from its K nearest neighbors.

Distance metric used: Euclidean distance

Normalization is essential due to distance-based calculations.
