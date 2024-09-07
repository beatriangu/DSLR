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

Histogram for All Subjects.
For example ; The Best Hand concept does not provide us with any significant insights.

<p align="left">
  <img src="https://github.com/beatriangu/DSLR/blob/main/Screenshot%20from%202024-09-07%2018-38-25.png" alt="Histogram for All Subjects" width="600"/>
</p>
Scatter
 """Null or weak correlation"""
<p align="left">
  <img src="https://github.com/beatriangu/DSLR/blob/main/Screenshot%20from%202024-09-07%2018-48-41.png" alt="Miniatura" width="600"/>
</p>

### Training and Evaluating:
`Accuracy` with standard parameters is `0.99`

Parameters for training, including batch size, are stored in [config.yaml](config.yaml)

* [logreg_train.py](logreg_train.py) saves `data/weights.pt`
(use `-v` flag for loss history visualization)

|stochastic GD                                    |                                             batch GD|                                                      GD|
|-------------------------------------------------|-----------------------------------------------------|--------------------------------------------------------|
|![histogram](readme_images/loss_batch_size_1.png)|![scatter_plot](readme_images/loss_batch_size_21.png)|![clusters_plot](readme_images/loss_batch_size_1600.png)|

* [logreg_predict.py](logreg_predict.py) takes `data/weights.pt` and saves `data/houses.csv`
* [evaluate.py](evaluate.py) - `logreg_train.py` + `logreg_predict.py` and evaluating on `dataset_truth.csv`
* [random_evaluate.py](random_evaluate.py) - training and evaluating on random splitted `dataset_train.csv`


<p align="left">
  <img src="https://github.com/user-attachments/assets/7235dc66-b8e3-435e-9bc0-4f933924d826" alt="Screenshot from 2024-09-06 16-37-46" width="150"/>
</p>
