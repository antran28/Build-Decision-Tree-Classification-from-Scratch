# 🌳Decision Tree Model from Scratch
This repository contains a Python implementation of a decision tree model built from scratch. Decision trees are a fundamental machine learning algorithm used for both classification and regression tasks. With this code, you can understand how decision trees work internally and gain insights into the core concepts behind their functioning.

## Features
- Implementation of a decision tree classifier.
- Supports both Gini impurity and entropy as splitting criteria.
- Allows you to set the maximum depth of the tree and the minimum number of samples required to split a node.
- Utilizes a binary tree structure for decision making.

## How to Use
1. Clone this repository to your local machine:
```python
git clone https://github.com/yourusername/decision-tree-from-scratch.git
```
2. Ensure you have the required dependencies installed, such as NumPy, Seaborn, and Matplotlib.

3. Import the DecisionTree class and create an instance with your desired parameters, such as max_depth and criterion.

4. Fit the decision tree to your training data using the fit method.

5. Make predictions on new data using the predict method.

6. Evaluate the model's performance by calculating metrics like accuracy.

7. Visualize the results using the provided plotting functions.

## Example
```python
# Create and fit the decision tree model
clf = DecisionTree(max_depth=4, criterion="gini")
clf.fit(X_train, y_train)

# Make predictions
y_pred = clf.predict(X_test)

# Calculate accuracy
accuracy = accuracy_score(y_test, y_pred)
print("Accuracy:", accuracy)

# Plot the results
plt.suptitle("Accuracy = {:.2f}".format(accuracy))
# Add your plotting code here
plt.show()
```
## Dataset
The code includes an example dataset generated using make_classification from scikit-learn for demonstration purposes. You can replace it with your own dataset.

## License
This repository is licensed under MIT License - see [License](LICENSE) for more details.

Happy coding! If you find this project useful, please consider giving it a star on GitHub.
___________________________________

<p>&copy; 2023 An Tran</p>
