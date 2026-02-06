# CS-4630-Learning-Activity Q3
## Dimensionality Reduction by PCA

### Overview
This project applies Principal Component Analysis (PCA) to the Iris dataset to reduce its dimensionality while preserving as much variance as possible.
The original four-feature dataset is transformed into two principal components and visualized to examine how well PCA separates the different iris species.

### Dataset
**Name:** Iris Dataset
**Source:** sklearn.datasets.load_iris
**Description:** The dataset consists of 150 samples of iris flowers with four features-
            - Sepal length
            - Sepal width
            - Petal length
            - Petal width

            Each sample belongs to one of three species-
            - Setosa
            - Versicolor
            - Virginica
No external data files are required, as the dataset can be loaded directly from scikit-learn.  

### How to Run
1. Python 3.8 or later
2. Jupyter Notebook (VS Code with Jupyter extension)
3. Install- pip install numpy pandas matplotlib scikit-learn
4. Update the working path to your path
5. Run the notebook

### Parameter Setup
- Must standardize the X component (mean = 0, standard deviation = 1). This is       required because PCA is sensitive to variable scaling.
- PCA Parameters: components = 2 (chosen for visualization purposes)

### How to Comprehend Results
The output will include a 2D scatter plot of two principal components.
- Each point represents an iris sample
- Colors indicate species
- Observe clustering patterns to understand how PCA separates species
