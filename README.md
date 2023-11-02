# Machine Learning Specialization

Due to historical reasons, this repository contains materials from two courses: 'Machine
Learning' offered by Stanford University and the
['Machine Learning Specialization'](https://www.deeplearning.ai/courses/machine-learning-specialization/)
offered by DeepLearning.AI. While the original link to the 'Machine Learning' course
offered by Stanford in 2015 is no longer available, all relevant materials have been
preserved within this repository.

## Description

### Machine Learning Specialization

#### C1W2: [Linear Regression](https://htmlpreview.github.io/?https://github.com/lionlai1989/machine-learning/blob/master/DeepLearningAI/C1-Supervised_Machine_Learning_Regression_and_Classification/W2A1-Linear_Regression/C1_W2_Linear_Regression.html)

**Linear regression** is one of the most widely used algorithms for predicting a wide
range of phenomena in fields like economics, social sciences, and engineering. It
achieves this by providing **continuous** predictions. This section provides everything
we need to know to implement a linear regression algorithm from the ground up. It
presents how to select an appropriate regression model, define a cost function, and
build a batch gradient descent approach to optimize a regression model.

<div style="text-align:center">
  <img src="./DeepLearningAI/C1-Supervised_Machine_Learning_Regression_and_Classification/W2A1-Linear_Regression/images/linear_regression.png" alt="Your Image Description" height="256">
  <p style="font-size: 14px; color: #777;">Linear regression fits samples with one feature.</p>
</div>

#### C1W3: [Logistic Regression](https://htmlpreview.github.io/?https://github.com/lionlai1989/machine-learning/blob/master/DeepLearningAI/C1-Supervised_Machine_Learning_Regression_and_Classification/W3A1-Logistic_Regression/C1_W3_Logistic_Regression.html)

Although linear regression is good at predicting continuous values, it's not the ideal
choice for tasks that require **discrete** outcomes, like **classification problems**.
In such cases, we turn to **logistic regression**, an algorithm that's better suited to
handling discrete predictions. In this section, it shows how to build a logistic
regression model from scratch and address the issue of overfitting by introducing a
regularization term into the logistic cost function, ensuring the accuracy of models
during inference.

<div style="text-align:center">
  <img src="./DeepLearningAI/C1-Supervised_Machine_Learning_Regression_and_Classification/W3A1-Logistic_Regression/images/figure 4.png" alt="Your Image Description" height="256">
  <p style="font-size: 14px; color: #777;">Logistic regression is employed to establish a decision boundary for two-feature samples by introducing polynomial terms as augmented features derived from the original two features.</p>
</div>

#### C2W1:

#### C2W2:

#### C2W3:

#### C2W4:

### Machine Learning Stanford

#### [Linear Regression]()

#### [Logistic Regression]()

#### [Multi-class Classification]()

#### [Neural Networks]()

#### [Regularized Linear Regression and Bias v.s. Variance]()

#### [Support Vector Machines]()

#### [K-means clustering and Principal Component Analysis]()

#### [Anomaly Detection and Recommender Systems]()

## Getting Started

All the results in Jupyter Notebook can be reproduced by following the instructions
below.

### Dependencies

Before you start, you need to make sure you have the following dependencies installed:

-   **Python-3.10:** Python-3.10 is used throughout all the solutions to the problems.

### Downloading

-   To download this repository, run the following command:

```shell
git clone https://github.com/lionlai1989/machine-learning
```

### Install Python Dependencies

-   Create and activate a Python virtual environment

```
python3.10 -m venv venv_machine_learning && source venv_machine_learning/bin/activate
```

-   Update `pip` and `setuptools`:

```
python3 -m pip install --upgrade pip setuptools
```

-   Install required Python packages in `requirements.txt`.

```
python3 -m pip install -r requirements.txt
```

### Running Jupyter Notebook

Now you are ready to go to each Jupyter Notebook and run the code. Please remember to
select the kernel you just created in your virtual environment `venv_machine_learning`.

## Contributing

Any feedback, comments, and questions about this repository are welcome. However, I will
politely decline all pull requests or merge requests. This repository is a record of my
learning journey, and I aim to maintain its independence.

## Authors

[@lionlai](https://github.com/lionlai1989)

## Version History

-   2.0.0
    -   Working on the course, Machine Learning Specialization, in 2023.
-   1.0.0
    -   Finish all the problems in the course of Machine Learning Stanford by 2015.

## Reference

-   Disable annoying tensorflow DEBUG message. Put the following code at the start of
    the nodebook.

```
import os
os.environ['TF_CPP_MIN_LOG_LEVEL'] = '3'  # or any {'0', '1', '2', '3'}. 3: NONE
```

<!--
Use "python3.10" and "numpy >= 1.20"

## Acknowledgments
Explore the inspiration and references listed here to further expand your knowledge and sharpen your skills.




Coursera: https://learn.udacity.com/courses/ud810

https://docs.google.com/spreadsheets/d/1ecUGIyhYOfQPi3HPXb-7NndrLgpX_zgkwsqzfqHPaus/pubhtml

Find time to do the assignments in the speard sheet above.

https://faculty.cc.gatech.edu/~afb/classes/CS4495-Fall2014/

### NOTE
Make github repository to public so that the images in jupyter notebook can be displayes correctly.


### Installation
Install `sudo apt-get install gfortran` for scipy.

C4W4A1 cannot be build because the model.json file cannot be read. We can build the model and read the weights.

It requires `python-3.7.6` `python-3.10`.
Install environment:
```
/usr/local/lib/python-3.7.6/bin/python3.7 -m venv venv_deep_learning && source venv_deep_learning/bin/activate && python3 -m pip install --upgrade pip setuptools
```

Install packages:
```
python3 -m pip install -r requirements.txt
``` -->

<!--
**If you want to learn about basic machine learning, please visit
[Machine Learning Stanford note](https://share.coursera.org/wiki/index.php/ML:Main#Course_Information). This website has precious materials which can give you a broad knowledge about machine learning.**

###Quick Guide:
1. Installing python3.
2. Installing numpy, matplotlib, scipy, scikit-learn and Pillow.
  ```
  sudo pip3 install numpy
  sudo pip3 install matplotlib
  sudo pip3 install scipy
  sudo pip3 install scikit-learn
  sudo pip3 install Pillow
  ```

3. Cloning from [https://github.com/lionlai1989/machineLearningStanford](https://github.com/lionlai1989/machineLearningStanford)
  ```
  git clone https://github.com/lionlai1989/machineLearningStanford
  ```
[Linear Regression](https://github.com/lionlai1989/machineLearningStanford/tree/master/ex1)<br>
[Logistic Regression](https://github.com/lionlai1989/machineLearningStanford/tree/master/ex2)<br>
[Multi-class Classification](https://github.com/lionlai1989/machineLearningStanford/tree/master/ex3)<br>
[Neural Networks](https://github.com/lionlai1989/machineLearningStanford/tree/master/ex4)<br>
[Regularized Linear Regression and Bias v.s. Variance](https://github.com/lionlai1989/machineLearningStanford/tree/master/ex5)<br>
[Support Vector Machines](https://github.com/lionlai1989/machineLearningStanford/tree/master/ex6)<br>
[K-means clustering and Principal Component Analysis](https://github.com/lionlai1989/machineLearningStanford/tree/master/ex7)<br>
[Anomaly Detection and Recommender Systems](https://github.com/lionlai1989/machineLearningStanford/tree/master/ex8)<br>

If you want to use this module, please read the *.py file in test folder. You should get a good understanding of using this module by reading test file. If not, please contact me. Any judgement and recommendation are welcomed.
Thank you.
pdfimages -all -png C1_W1.pdf image_w1/
 -->
