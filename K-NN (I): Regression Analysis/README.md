K-Nearest Neighbors algorithm is probably the simplest widely used model in machine learning. In
spite of its simplicity, K-NN has proven to be incredibly powerful in various machine-learning
applications. Although it’s far more popular in classification problems, K-NN can also be used in any
regression task. The aim of this problem is to investigate how K-NN can be equally effective when
the target variable is continuous in nature.

First, consider a simple regression problem with one dependent
variable and one independent variable. Here, the goal is to
predict an animal’s body weight given its brain weight. You will
use “animals_weight.txt” dataset which contains a list of brain
weight and body weight measurements from a bunch of animals.

a. Given the following brain weights of some unknown animals, predict their body weight using 1-NN, 3-NN and 5-NN models.
![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/c9e25f77-62c2-456d-8ba6-ac326fefa9b4)

b. Plot the regression line considering 1-NN, 3-NN and 5-NN models.

1-NN:

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/8d94ad11-26d9-4143-9ed4-34779873831c)

3-NN:

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/06dbc0a5-3b92-4d29-ab62-a441dcf7b4da)

5-NN:

![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/064b7cc8-e56d-49c8-b63b-693088363d75)

Now let’s consider a more complicated problem, i.e. multivariate regression. You are given a dataset, “wine_quality.csv”, containing 1600 red Vinho Verde wine samples. The goal is to model wine quality based
on 11 physicochemical measurements.

c. Given the following table containing five set of physicochemical measurements, predict the corresponding wine qualities using 1-NN, 3-NN and 5-NN models.
![image](https://github.com/niloufareshghi/Pattern-Recognition/assets/47944007/9a1f7674-ff29-4b1f-9d8a-1091bd7519a4)
