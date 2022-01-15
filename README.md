**20BRS1077**
# Problem Statement 
This data set consists of Placement data of students in a XYZ campus. It includes secondary and higher secondary school percentage and specialization. It also includes degree specialization, type and Work experience and salary offers to the placed students
## Dataset

The dataset used is the Campus Recruitment https://www.kaggle.com/benroshan/factors-affecting-campus-placement from Kaggle. 

The class labels are:
<br>
-
**-sl_no:** Serial Number

**-gender:** Gender- Male='M',Female='F'

**-ssc_p:** Secondary Education percentage- 10th Grade

**-ssc_b:** Board of Education- Central/ Others

**-hsc_p:** Higher Secondary Education percentage- 12th Grade

**-hsc_b:** Board of Education- Central/ Others

**-hsc_s:** Specialization in Higher Secondary Education

**-degree_p:** Degree Percentage

**-degree_t:** Under Graduation(Degree type)- Field of degree education

**-workex:** Work Experience

**-etest_p:** Employability test percentage ( conducted by college)

**-specialisation:** Post Graduation(MBA)- Specialization

**-mba_p:** MBA percentage

**-status:** Status of placement- Placed/Not placed

**-salary:** Salary offered by corporate to candidates

## Model(s) Used

This needs to be a description of the model used and a brief overview of how it works in theory (e.g taken of a CNN Model): 

The network architecture used was a basic CNN model, with Max Pooling and ReLU Activation functions. Input images are resized to an optimal size and then fed into the **Convolutional layer**. These images are converted to their pixel values, which can be imagined as a three-dimensional matrix for the purpose of visualization. The **Convolutional layer** has a kernel. This kernel is generally a small matrix of specified kernel size mxnx3 (3 for RGB images). 
<br>

**Rectified Linear Unit (ReLU)** is the activation layer used in CNNs.The activation function is applied to increase non-linearity in the CNN. Images are made of different objects that are not linear to each other.


**Max Pooling:** A limitation of the feature map output of Convolutional Layers is that they record the precise position of features in the input. This means that small movements in the position of the feature in the input image will result in a different feature map. This can happen with re-cropping, rotation, shifting, and other minor changes to the input image. A common approach to addressing this problem from signal processing is called down sampling. This is where a lower resolution version of an input signal is created that still contains the large or important structural elements, without the fine detail that may not be as useful to the task.

## Future Work
Good ideas or strategies that you were not able to implement which you think can help  improve performance.