**Aim:** Implement Polynomial Curve fitting using the polyfit function

**Theory:** 

Polynomial curve fitting:
Polynomial curve fitting is a mathematical technique used to approximate a relationship between two variables using a polynomial function. It has various applications in fields such as statistics, engineering, physics, economics, and more.  It is a very valuable tool in data analysis.
some common applications of polynomial curve fitting: 
Data Modeling, Interpolation and Extrapolation, Function Approximation Signal Processing, Regression Analysis, Scientific Research.
A Simple Regression Problem 
• We observe a real-valued input variable x and we wish to use this observation to predict the value of a real-valued target variable t. 
• We use synthetically generated data from the function sin(2πx) with random noise included in the target values. – A small level of random noise having a Gaussian distribution 
• We have a training set comprising N observations of x, written x ≡ (x1, . . . , xN ) T, together with corresponding observations of the values of t, denoted t ≡ (t1, . . . , tN ) T. 
• Our goal is to predict the value of t for some new value of x,
A training data set of N = 10 points, (blue circles),
 • The green curve shows the actual function sin(2πx) used to generate the data. 
 • Our goal is to predict the value of t for some new value of x, without knowledge of the green curve


![image](https://github.com/AdityaPatil0718/Polynomial-Curve-fitting/assets/128233555/43f4c56e-e011-4d27-8784-ac657edc0f96)
![image](https://github.com/AdityaPatil0718/Polynomial-Curve-fitting/assets/128233555/d2813953-4ddb-4655-9427-a4904e3a12c4)

We try to fit the data using a polynomial function of the form
 



**Conclusion:**
Polynomial curve fitting using the polyfit function provides a simple and effective way to approximate the relationship between variables. 
