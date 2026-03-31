# iris-flower-classifier-
Iris Flower Classification using KNN | A simple Machine Learning project that classifies iris species based on sepal and petal measurements using Python and Scikit-learn.
# Iris Flower Classification using Machine Learning

## Project Overview
This project is a simple **Machine Learning classification model** built using the famous **Iris dataset**. The goal is to classify iris flowers into three species based on their physical features:
* Setosa
* Versicolor
* Virginica

The model uses the **K-Nearest Neighbors (KNN)** algorithm to perform classification.

## Dataset

The dataset used in this project is the **Iris dataset**, which contains 150 samples with the following features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width
* Class (Species)

Dataset source:
[https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data](https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data)

## Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/iris-classifier.git
cd iris-classifier
```

2. Install required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Usage

Run the Python script:

```bash
python iris_classifier.py
```

## Model Details

* Algorithm: **K-Nearest Neighbors (KNN)**
* Evaluation Metrics:

  * Accuracy Score
  * Classification Report


## Workflow

1. Load dataset from URL
2. Assign column names
3. Perform exploratory data analysis (EDA)
4. Split dataset into training and testing sets
5. Train the KNN model
6. Evaluate model performance


## Code Snippet

```python
import pandas as pd

url  = "https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data"
column_names = ["sepal_length", "sepal_width", "petal_length", "petal_width", "class"]

iris_data = pd.read_csv(url, names=column_names)
print(iris_data.head())
```


## Example Output

* Accuracy: ~95% (depends on K value and split)
* Detailed classification report showing precision, recall, and F1-score

## Visualizations (Optional)

You can enhance the project by adding:

* Pairplots using Seaborn
* Heatmaps
* Feature distribution plots

## Future Improvements

* Hyperparameter tuning (finding optimal K value)
* Try other models (SVM, Decision Tree, Random Forest)
* Deploy as a web app using Flask or Streamlit
* Add cross-validation

## Contributing

Feel free to fork this repository and submit pull requests for improvements.

## License

This project is open-source and available under the MIT License.

## Author

Divyanshi Mohanty
GitHub: [https://github.com/divyanshi-code-creator](https://github.com/divyanshi-code-creator)

⭐ If you like this project, don’t forget to star the repo!
