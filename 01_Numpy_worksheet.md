# Numpy

In this worksheet, we will work through some of the functions within the Numpy package in python. More information about what you can do with numpy, visit: 
https://numpy.org/devdocs/user/quickstart.html   

----  

## Creating Arrays:  
1. 	There are two ways in which one can create an array between two bounds:

 ```python
 numpy.linspace()
```
```python
 numpy.arange()
```
 
  Which of these two would you use to create an array from 0 to 100 with 1000 array elements?   

2. With this choice in mind, open a new notebook in jupyter lab, import the numpy package and create an array from -10 to 10 with 101 elements in the array.

3. Using the array from part 2, we are going to create a variable that holds the solution to the equation:
   <p align="center">
   $$y = x^3 + 5x^2 - (1/3)x - 20$$
   
   In which x is the array generated in part 2, you will find the function `numpy.power()` useful for this task.   
   Please name the variable that holds the output of this function, y.

4. Numpy contains functions that allow you to find the minimum and maximum values of an array, what are they?  

5.	In a new cell in jupyter lab, use the functions from part 4 to find the minimum and maximum values of the array y from part 3.  

6.	Use the function `numpy.round()` to round the answers to part 5 to 3 decimal places.  

7.	Try to find the location of the largest y value in the array using the function `numpy.where()`.  

8.	Use the index found in part 7 to find the value of the array x, generated in part 2, that corresponds to the maximum value of y.

9. What happens if you repeat part 7, but search for the index corresponding to  maximum value of y rounded to 3 decimal places?  
If this is different to the answer in part 7, why might this be?

10. Use `numpy.mean()` to find the mean value of the y array from part 3.

11. It is possible to select all values that meet the criteria of a logical function (great than, less than or equal to, ect….).
    Use the following code to find the number of points in the array created in part 3 that are below 0:   
<p align="center">
$sub\_zero=y[y<0]$
  <p>
	How many elements in the array y, created in part 3 are below 0? 

12.	Can you modify the code in part 11 to find all the values that are below 10 but above -10?   
How many values in the array y lie between -10 and 10?

## Creating Arrays: 

13. Import the matplotlib package using the following command: 
```python
import matplotlib.pyplot as plt
```
14.	To plot the data as a scatter plot, we will use the function:
```python
plt.scatter()
```
The following URL describes the functions that can be used to modify your scatter plot away from the default settings:  
<https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.scatter.html>  
Using the information on this page, create a scatter plot for the arrays in part 2 and 3 with the following characteristics: 
- The markers for the datapoints should be crosses  
- There should be a dashed line between each of the datapoints
- The marker colour should be black

15. In the same cell as the graph is created, add the following lines:
    ```python
    plt.xlabel('Distance')
    plt.ylabel('Counts')
    plt.title('Distance vs Counts in Python')
    ```

16. Use the function `plt.plot()` to add in a solid magenta line that goes from the minimum to the maximum value of the array created in part 2, and has every y value equal to the mean value generated in part 10.  
What is the minimum number of datapoints required to create this line? 









   
