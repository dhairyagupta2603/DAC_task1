**20BRS1077**
# Problem Statement

This data set consists of Placement data of students in a XYZ campus. It includes secondary and higher secondary school percentage and specialization. It also includes degree specialization, type and Work experience and salary offers to the placed students.
## Dataset

The dataset used is the [Campus Recruitment](https://www.kaggle.com/benroshan/factors-affecting-campus-placement) from Kaggle.

The class labels are:
<br>
<ol>
    <li>**sl_no:** Serial Number</li>
    <li>**gender:** Gender- Male='M',Female='F'</li>
    <li>**ssc_p:** Secondary Education percentage- 10th Grade</li>
    <li>**ssc_b:** Board of Education- Central/ Others</li>
    <li>**hsc_p:** Higher Secondary Education percentage- 12th Grade</li>
    <li>**hsc_b:** Board of Education- Central/ Others</li>
    <li>**hsc_s:** Specialization in Higher Secondary Education</li>
    <li>**degree_p:** Degree Percentage</li>
    <li>**degree_t:** Under Graduation(Degree type)- Field of degree education</li>
    <li>**workex:** Work Experience</li>
    <li>**etest_p:** Employability test percentage ( conducted by college)</li>
    <li>**-specialisation:** Post Graduation(MBA)- Specialization</li>
    <li>**mba_p:** MBA percentage</li>
    <li>**status:** Status of placement- Placed/Not placed</li>
    <li>**salary:** Salary offered by corporate to candidates</li>
</ol>

## Model(s) Used
I used 2 classification algorithms on the dataset, these are discussed below

### 1. Decision Trees:
Decision Trees are a non-parametric supervised learning method used for classification and regression. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features.
A tree can be seen as a piecewise constant approximation. Decision trees use multiple algorithms to decide to split a node into two or more sub-nodes. The creation of sub-nodes increases the homogeneity of resultant sub-nodes. 
Purity of the node increases with respect to the target variable. The decision tree splits the nodes on all available variables and then selects the split which results in most homogeneous sub-nodes.

### 2. Logistic Regression
Logistic regression (LR) is basically a supervised classification algorithm. In a classification problem, the target variable(or output), y, can take only discrete values for a given set of features(or inputs),X.
The model builds a regression model to predict the probability that a given data entry belongs to the category numbered as “1”. Just like Linear regression assumes that the data follows a linear function, Logistic regression models the data using the sigmoid function.
The setting of the threshold value is a very important aspect of Logistic regression and is dependent on the classification problem itself.
In this particular case, LR is binomial, i.e., target variable can have only 2 possible types: “0” or “1” which represent "caffeine is not present in considerable amount" for "0" and vice-versa.
## Future Work
Using heatmaps and convolution matrix to delve deeper into data visualization and improve the prediction accuracy by using more advanced and varied classification algorithms.
