# Analysis-of-Kernel-Ridge-Regression-and-Error-Bound
1. we randomly generated data according to Gaussian distribution.  
2. After splitting the data, we trained and evaluated it on the Kernel Ridge regression model.  
3. we varied the parameter m (number of samples) on which Kernel Ridge regression error bound depends on, we repeated the first two steps. 
4. we compared the experimental results versus predictions from theory.  The goal was to observe if the experimental test error decays as 1/sqrt(m) for a fixed d (number of features). We plotted a graph [Test error for sample size m] x sqrt(m) versus m to verify that the resulting graph is approximately a graph of constant function. 
We made a similar procedure by varying the parameter d (number of features). To compare the results, we plotted a graph [Test error for sample size m] / d^2 versus d to verify that the resulting graph is approximately a graph of constant function. 
5. The experiments showed that еhe difference between Test Error and Train Error does not exceed the Theoretical Bound with some exceptions. 
6.Finally, we implemented similar steps for the California housing dataset as for the randomly generated data. The results on the real data were similar, however with more deviations.
