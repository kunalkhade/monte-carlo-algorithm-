# monte-carlo-algorithm-
Implementation of Monte carlo algorithm using OpenMP (Parallel Programming) 

## Program Description
A Monte Carlo method is a means of using random numbers to compute
something that is not random.
1. Define a domain : 1x1 Square cube with side 1 unit.
2. Generate Random Inputs : Generate Random numbers inside of square
3. Deterministic Computation : Mark generated input as a ’True’ or ’False’. In this case if input is inside of quarter circle then it will program will mark it a ’True’ sample and otherwise ’False’.
4. Get the result : Analyze the result and come tu conclusion.

## Compilation process
1 . gcc -g -Wall -fopenmp -o mc MonteCarlo.c -lm

2 . ./mc Value (number of iterations in list)

## Results 
### Result : Iteration 10000000 Darts pi value was 3.141697 with error -0.000105 
