# Decision Tree Model for Mushroom Classification

This project implements a Decision Tree Model for classifying mushrooms as either edible or poisonous based on a given dataset which contains information about various mushroom species, including features such as cap shape, odor, and habitat, to make classification predictions.  
The project is implemented in Python and Jupyter Notebook, using the following modules: 'pandas', 'numpy', and 'matplotlib'.

## Project Files

- **decision_tree_model.ipynb**: Jupyter Notebook containing the code and explanations for the project.
- **decision_tree_model.py**: Python script containing the implementation of the Decision Tree model and related functions.
- **dagaricus-lepiota.csv**: Dataset which contains descriptions of hypothetical mushroom samples.

## Dataset

The project uses the 'agaricus-lepiota.csv' dataset, which contains descriptions of hypothetical mushroom samples. Each mushroom is labeled as either edible or poisonous. The dataset includes 8124 observations with 21 features and the class label.

## Project Structure

The project is structured as follows:

1. **Data Preprocessing**: The dataset is loaded using pandas and any missing values are removed. It is then split into training and testing sets.
2. **Impurity Measures**: Implementation of Gini impurity and Entropy impurity measures used for evaluating the quality of splits in the Decision Tree.
3. **Goodness of Split**: Calculation of the Goodness of Split and Gain Ratio to determine the best feature for splitting the data.
4. **Building the Decision Tree**: Implementation of the DecisionNode class and the build_tree function to construct the Decision Tree. The model supports both Gini and Entropy as impurity measures.
5. **Tree Evaluation**: The accuracy of the Decision Tree is calculated on both the training and testing datasets for different impurity measures and gain ratio settings. The best-performing tree is selected for further analysis.
6. **Depth Pruning**: Investigation of the effect of the maximum depth of the tree on training and testing accuracies. Different maximum depths are explored, and the results are visualized.
7. **Chi-Square Pre-Pruning**: Evaluation of the effect of chi-square pre-pruning on training and testing accuracies. Different p-value cut-off values are tested, and the results are visualized.
8. **Number of Nodes**: Counting and printing the number of nodes in the best-performing trees.
9. **Printing the Tree**: Provided function to print the Decision Tree for debugging purposes.

## Running the Code

To run the code, follow these steps:

1. Open the Jupyter Notebook file **decision_tree_model.ipynb**.
2. Execute each cell in the notebook in order, paying attention to the explanations and code comments.
3. Analyze the results and visualizations to understand the performance of the Decision Tree model.
   
## Requirements 

Please ensure you have the required Python version and modules installed to execute the code successfully:

- Python 3.6 or above
- Required Python libraries: 'pandas', 'numpy', 'matplotlib'

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required libraries.

-pip install numpy pandas matplotlib



## Credits

This project was completed as part of the "Machine Learning" course at Reichman University.

