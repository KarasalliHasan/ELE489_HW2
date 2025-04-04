# ELE489_HW2

#  Banknote Authentication with Decision Tree Algorithm

Applies a Decision Tree Classifier to the **Banknote Authentication Dataset** to distinguish between real and fake banknotes.

##  Dataset

The dataset used is the UCI Banknote Authentication dataset. It includes the following features:

- **Variance**
- **Skewness**
- **Kurtosis**
- **Entropy**
- **Class** (0 = fake, 1 = authentic)


## Steps
- **Data Loading**
  - Scatter plots of feature pairs to understand relationships
- **Preprocessing**
  - Splitting into training and testing sets
- **Modeling**
  - Training with `DecisionTreeClassifier` using various parameters
  - Evaluating with accuracy score, classification report
- **Visualization**
  - Confusion matrix 
  - Feature importance plot
  - Tree structure with `plot_tree()`

##  Results

- Achieved accuracy ranging between **94%–98%** depending on parameter tuning.
- Feature importance analysis showed that **variance** is the most influential features.


##  Tools & Libraries

- Python 3.x
- pandas
- matplotlib
- numpy
- scikit-learn
- Banknote Authentication Dataset from https://archive.ics.uci.edu/dataset/267/banknote+authentication


