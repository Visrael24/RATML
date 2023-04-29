# RATML

Slides:
Val - 3, 4
Alex - 5, 6
Becca - 7, 8
Matt - 9, 10, 11(Resources)

## Assessment 9

#### Introduction
This project aims to inform our classmates and instructors on the benefits and use-cases of a DecisionTree() model/models for Machine-Learning

#### Target Dataset
Our algorithm will be trained on 3 separate datasets: Cars93[93, 28], Data_Science_Salaries[3755, 11], Melborne_Housing_Data[13580, 21]
                       Note: The values within the brackets depict the shape of the dataset.

#### Advantages and Disadvantages
##### Pros:
        - Decision Trees are easy to interpret and understand, making them a popular choice for data analysis and decision-making.
        - They work well with both categorical and numerical data, making them a versatile tool.
        - Decision Trees can handle missing values and noisy data without much pre-processing.
        - They can help identify relationships between variables and can be used for feature selection.
        - They can be used for both classification and regression tasks.
##### Cons:
        - Decision Trees are prone to overfitting, especially when they are too complex or the data is noisy.
        - They are sensitive to changes in the data, which can cause different splits and predictions.
        - They can be biased towards features with many levels, resulting in a poorly generalized model.
        - They can easily become too complex, making it difficult to interpret the results and the underlying decision-making process.
        - They may not perform well on data with a high degree of multicollinearity, as they may end up splitting on correlated features.


#### How the Algorithm Works
The Decision Tree algorithm creates a tree-like model of decisions and their possible consequences, based on the data inputs. It starts with a single node representing the entire dataset and recursively splits the dataset into smaller subsets based on the values of one or more input features. Each split creates a new decision node in the tree, with branches leading to one or more child nodes representing the subsets resulting from the split. This process continues until a stopping criterion is met, such as a predefined maximum tree depth, minimum number of samples per leaf, or a minimum improvement in predictive accuracy.

To make a prediction on a new data point, the algorithm starts at the root node of the tree and follows the appropriate branches based on the values of the input features. It eventually reaches a leaf node representing a specific outcome or class label. This outcome or class label is then used as the predicted value for the new data point.

The algorithm uses various criteria to determine which features to split on at each node, such as information gain or Gini impurity. These criteria measure the amount of information provided by each feature in predicting the target variable and aim to find the optimal split that maximizes the information gain or minimizes the impurity of the resulting subsets.

Overall, the Decision Tree algorithm works by recursively splitting the dataset based on the values of input features, creating a tree-like model of decisions and their consequences, and making predictions by traversing the tree from the root node to the appropriate leaf node.
