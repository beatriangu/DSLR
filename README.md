# DSLR
DataScience x Logistic Regression - School-42 project

#### Goals:
* Learn how to read a dataset, to visualize it in different ways, to select and clean unnecessary information from your data.
* Implement one-vs-all logistic regression that will solve classification problem

Look at [subject.pdf](readme_images/subject.pdf) for more information

### Data Analysis
To show the dataframe from a complete csvfile with all types of values ​​and with all subjects
<p align="left">
  <img src="https://github.com/beatriangu/DSLR/blob/main/Screenshot%20from%202024-09-07%2018-11-43.png" alt="Miniatura" width="300"/>
</p>

To display dataframe exactly as in the subject . Only numerical values, transposed texts and first four columns of Features
<p align="left">
  <img src="https://github.com/beatriangu/DSLR/blob/main/Screenshot%20from%202024-09-07%2018-18-37.png" alt="Miniatura" width="300"/>
</p>

To display a dataframe with only numerical values, transposed axes and first four Subjects.
<p align="left">
  <img src="https://github.com/beatriangu/DSLR/blob/main/Screenshot%20from%202024-09-07%2018-23-34.png" alt="Miniatura" width="300"/>
</p>

## Data Visualitation

Histogram : show course marks distribution.
For example ; The Best Hand concept does not provide us with any significant insights.

<p align="left">
  <img src="https://github.com/beatriangu/DSLR/blob/main/Screenshot%20from%202024-09-07%2018-38-25.png" alt="Histogram for All Subjects" width="600"/>
</p>

Scatter: how values for two courses using Cartesian coordinates.

Null or weak correlation example between Arithmancy and Care of Magical Creatures
<p align="left">
  <img src="https://github.com/beatriangu/DSLR/blob/main/Screenshot%20from%202024-09-07%2018-54-00.png" alt="Miniatura" width="600"/>
</p>

Pair Plot: This scatter plot matrix visualizes the pairwise relationships between each subject and all other subjects. It allows you to see how each pair of subjects correlates with each other.

<p align="left">
<img src="https://github.com/beatriangu/DSLR/blob/main/Screenshot%20from%202024-09-07%2019-28-14.png" alt="Miniatura" width="300"/>
</p>

### Training and Evaluating:

python3 logreg_train.py [-h] [-v] dataset

<img src="https://github.com/beatriangu/DSLR/blob/main/Screenshot%20from%202024-09-07%2019-44-48.png" alt="Thumbnail" width="300"/>

python3 logreg_predict.py dataset weights
Generate a file with all predictions for a given dataset

Evaluate.py 
<img src="https://github.com/beatriangu/DSLR/blob/main/Screenshot%20from%202024-09-07%2019-56-50.png" alt="Thumbnail" width="300"/>


<p align="left">
  <img src="https://github.com/user-attachments/assets/7235dc66-b8e3-435e-9bc0-4f933924d826" alt="Screenshot from 2024-09-06 16-37-46" width="150"/>
</p>
