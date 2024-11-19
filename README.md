# ML_in_python_practice
this project was done in order to practice machiene learning fundamentals in python by using the iris flower dataset and using python modules that are tailored for DS and ML

instructions:
1. have juypter notebook or any other pyton compatable IDE installed to deploy the code on your local machiene
2. You don't need to know everything this mini-project was designed to help you understand how machiene learning works when it comes to stasticts; the code takes the iris flower dataset and to peek the data, make and evaluate predictions.
3. downloade the code analyse it and work out how everything works.



expected Output:

**OUTPUT #1**: 

sepal-length  sepal-width  petal-length  petal-width        class
0            5.1          3.5           1.4          0.2  Iris-setosa
1            4.9          3.0           1.4          0.2  Iris-setosa
2            4.7          3.2           1.3          0.2  Iris-setosa
3            4.6          3.1           1.5          0.2  Iris-setosa
4            5.0          3.6           1.4          0.2  Iris-setosa
5            5.4          3.9           1.7          0.4  Iris-setosa
6            4.6          3.4           1.4          0.3  Iris-setosa
7            5.0          3.4           1.5          0.2  Iris-setosa
8            4.4          2.9           1.4          0.2  Iris-setosa
9            4.9          3.1           1.5          0.1  Iris-setosa
10           5.4          3.7           1.5          0.2  Iris-setosa
11           4.8          3.4           1.6          0.2  Iris-setosa
12           4.8          3.0           1.4          0.1  Iris-setosa
13           4.3          3.0           1.1          0.1  Iris-setosa
14           5.8          4.0           1.2          0.2  Iris-setosa
15           5.7          4.4           1.5          0.4  Iris-setosa
16           5.4          3.9           1.3          0.4  Iris-setosa
17           5.1          3.5           1.4          0.3  Iris-setosa
18           5.7          3.8           1.7          0.3  Iris-setosa
19           5.1          3.8           1.5          0.3  Iris-setosa

**OUTPUT #2**:
       sepal-length  sepal-width  petal-length  petal-width
count    150.000000   150.000000    150.000000   150.000000
mean       5.843333     3.054000      3.758667     1.198667
std        0.828066     0.433594      1.764420     0.763161
min        4.300000     2.000000      1.000000     0.100000
25%        5.100000     2.800000      1.600000     0.300000
50%        5.800000     3.000000      4.350000     1.300000
75%        6.400000     3.300000      5.100000     1.800000
max        7.900000     4.400000      6.900000     2.500000


**OUTPUT #3**:
class
Iris-setosa        50
Iris-versicolor    50
Iris-virginica     50


**OUTPUT #4:** data visualization of sepal and petal length,width


![image](https://github.com/user-attachments/assets/a08f76b4-9f0c-450a-aec6-1efdf2f8c7e3)



**OUTPUT #5:** data visualizationi of the same via bar graphs:

![image](https://github.com/user-attachments/assets/7c458cd8-352b-4616-b3ef-6c35fb14bb76)


**OUTPUT #6:** Multivariate Plots

Now we can look at the interactions between the variables.

![image](https://github.com/user-attachments/assets/ea56cd70-2913-4552-b05f-59138ecf10d3)



**OUTPUT #7**: Algorithmic Comparison

![image](https://github.com/user-attachments/assets/c2e41f43-70d6-4ce3-8a94-5b98d4d89212)


**OUTPUT #8**: 
the output for making predictions:

0.9666666666666667
[[11  0  0]
 [ 0 12  1]
 [ 0  0  6]]
                 precision    recall  f1-score   support

    Iris-setosa       1.00      1.00      1.00        11
Iris-versicolor       1.00      0.92      0.96        13
 Iris-virginica       0.86      1.00      0.92         6

       accuracy                           0.97        30
      macro avg       0.95      0.97      0.96        30
   weighted avg       0.97      0.97      0.97        30




