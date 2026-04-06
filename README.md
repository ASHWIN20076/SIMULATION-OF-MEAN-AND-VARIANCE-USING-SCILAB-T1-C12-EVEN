# SIMULATION-OF-MEAN-AND-VARIANCE-USING-SCILAB-T1-C12-EVEN
AIM:

To write a program for mean, variance and cross correlation in SCILAB and verify the output.

#EQUIPMENTS NEEDED:

.Computer with i3 Processor

.SCI LAB

ALGORITHM:

Define the Function: Specify the function you want to simulate. For example, f(x)=sin⁡(x)f(x)=sin(x) or any other function.
Generate Sample Points: Decide on the range and the number of sample points. Generate these sample points within the desired range.
Evaluate the Function: Compute the function values at each of these sample points.
Compute Mean, Variance and Cross Correlation: Use Scilab's functions to calculate the mean and variance of the computed function values.
Display Results: Output the computed mean variance and Cross Correlation

PROCEDURE:

1.Refer Algorithms and write code for the experiment.

2.Open SCILAB in System

3.Type your code in New Editor

4.Save the file

5.Execute the code If any Error, correct it in code and execute again

6.Verify the generated results

PROGRAM:
```
clc;
clear;

// Given data
X = [12 13 14 15 16];

// Number of elements
N = length(X);

// Calculate Mean
mean_value = sum(X) / N;

// Calculate Variance
variance_value = sum((X - mean_value).^2) / N;

// Display Results
disp("Mean = ");
disp(mean_value);

disp("Variance = ");
disp(variance_value);
```
Calculation:

![b344b1c0-3196-4648-9d41-a4eaa3f846b4](https://github.com/user-attachments/assets/2da47a69-eee8-4e07-be1f-0ae63e1b561e)

![ce955377-b778-4b4b-9596-24122262a4ee](https://github.com/user-attachments/assets/f32ff484-c998-4028-bef4-9ab182c6611c)

OUTPUT :

<img width="881" height="542" alt="Screenshot 2026-03-12 104550" src="https://github.com/user-attachments/assets/db8fc372-7e76-4d72-91c3-26fbc658f9af" />

RESULT:
Thus SIMULATION-OF-MEAN-AND-VARIANCE-USING-SCILAB is experimentally done and the output is verified
