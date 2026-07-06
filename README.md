# Machine Learning Portfolio

A collection of hands-on machine learning and deep learning projects, implemented in Python using **scikit-learn**, **TensorFlow/Keras**, and the scientific Python stack. Each notebook is a self-contained study of a core ML topic — from classical algorithms to convolutional neural networks — covering data preparation, model building, evaluation, and hyperparameter tuning.

This repository grew out of my university coursework and represents my journey through the fundamentals of modern machine learning.

## Skills Demonstrated

- **Supervised learning** — classification and regression with linear models, SVMs, decision trees, and k-Nearest Neighbors
- **Ensemble methods** — bagging, random forests, boosting (AdaBoost, Gradient Boosting), and voting classifiers
- **Unsupervised learning** — clustering (K-Means, DBSCAN) and dimensionality reduction (PCA)
- **Deep learning** — building, training, and tuning neural networks and CNNs with TensorFlow/Keras
- **Model evaluation** — cross-validation, confusion matrices, accuracy/F1/silhouette metrics, and error analysis
- **Practical workflow** — feature scaling, pipelines, polynomial features, and model persistence

## Tech Stack

`Python` · `scikit-learn` · `TensorFlow` · `Keras` · `NumPy` · `pandas` · `Matplotlib` · `Jupyter`

## Contents

| Notebook | Topic | Key Techniques |
|---|---|---|
| [Perceptron.ipynb](Perceptron.ipynb) | Perceptron & basics of neural units | Perceptron, first Keras models |
| [RegressionKNN.ipynb](RegressionKNN.ipynb) | Regression | Linear & polynomial regression, KNN regression |
| [MNISTClassification.ipynb](MNISTClassification.ipynb) | Image classification | SGD classifier, cross-validation, confusion matrix |
| [SVM.ipynb](SVM.ipynb) | Support Vector Machines | LinearSVC, kernels, scaling pipelines |
| [DecisionTrees.ipynb](DecisionTrees.ipynb) | Decision Trees | Classification & regression trees, tree visualization |
| [EnsembleMethods.ipynb](EnsembleMethods.ipynb) | Ensemble learning | Random forests, AdaBoost, Gradient Boosting, voting |
| [Clustering.ipynb](Clustering.ipynb) | Clustering | K-Means, DBSCAN, silhouette analysis |
| [DimensionalityReduction.ipynb](DimensionalityReduction.ipynb) | Dimensionality reduction | PCA, standardization |
| [FashionMnistNN.ipynb](FashionMnistNN.ipynb) | Neural networks | Dense networks on Fashion-MNIST / California Housing |
| [ConvolutionalNeuralNetworks.ipynb](ConvolutionalNeuralNetworks.ipynb) | Deep learning | CNNs with TensorFlow Datasets |
| [HyperparameterTuning.ipynb](HyperparameterTuning.ipynb) | Model optimization | RandomizedSearchCV, KerasRegressor tuning |

## Getting Started

```bash
# Clone the repository
git clone https://github.com/PiotrSzczachor/Machine-Learning.git
cd Machine-Learning

# (Recommended) create a virtual environment
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate

# Install dependencies
pip install numpy pandas matplotlib scikit-learn tensorflow tensorflow-datasets scikeras graphviz pydot

# Launch Jupyter
jupyter notebook
```

Open any notebook and run the cells top to bottom. Each one is independent and downloads its own datasets (e.g. via `fetch_openml` or `tensorflow_datasets`).

