# Decision Tree Classification Application (Karar Ağacı Sınıflandırma Uygulaması)

This project is a mandatory assignment for the Machine Learning course, focusing on the application of the Decision Tree algorithm. The primary goal is to build a classification model using the **entropy** criterion on a given small dataset and to manually calculate and interpret the core mechanics of the algorithm (specifically Entropy and Information Gain).

## Project Details

### Dataset

The dataset used for this application determines whether tennis will be played (`PlayTennis`) based on various weather conditions (`Outlook`, `Temperature`, `Humidity`, `Wind`). The dataset consists of 10 observations.

| Outlook | Temperature | Humidity | Wind | PlayTennis |
| :---: | :---: | :---: | :---: | :---: |
| Sunny | Hot | High | Weak | No |
| Overcast | Mild | Normal | Strong | Yes |
| ... | ... | ... | ... | ... |

### Methods and Libraries Used

* **Language:** Python
* **Data Preparation:** The table was first created as a Pandas DataFrame.
* **Preprocessing:** `LabelEncoder` from Scikit-learn was used to convert categorical variables into numerical values.
* **Model:** `DecisionTreeClassifier` from Scikit-learn was employed for classification.
* **Criterion:** The model was built using `criterion='entropy'`.

### Expected Deliverables and Analysis

The project includes both coding implementation and theoretical manual calculations.

#### 1. Decision Tree Visualization
* The trained model was visualized using `plot_tree()` or Graphviz.

#### 2. Manual Calculations (Entropy & Information Gain)
* Entropy and Information Gain calculations were performed manually.
* **Total Entropy ($E(S)$):** Calculated to measure the initial impurity of the dataset

