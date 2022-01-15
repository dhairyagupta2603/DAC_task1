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
### Support Vector Machine

A Support Vector Machine is a supervised classification technique that can actually get pretty complicated but is pretty intuitive at the most fundamental level.
<br>
Let’s assume that there are two classes of data. A support vector machine will find a hyperplane or a boundary between the two classes of data that maximizes the margin between the two classes (see below). There are many planes that can separate the two classes, but only one plane can maximize the margin or distance between the classes

### K-Nearect Neighbour

The KNN algorithm assumes that similar things exist in close proximity. In other words, similar things are near to each other.
<br>
most of the time, similar data points are close to each other. The KNN algorithm hinges on this assumption being true enough for the algorithm to be useful. KNN captures the idea of similarity (sometimes called distance, proximity, or closeness) with some mathematics we might have learned in our childhood— calculating the distance between points on a graph.

## Future Work

May Do classifications with other models
