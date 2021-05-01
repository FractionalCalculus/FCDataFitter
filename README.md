# FCDataFitter
#### Data Fitting Toolbox Employing Fractional Calculus 

### Way to Go

It started from an idea, find a better formulation for MOND  
Next I thought about how to do data fitting using Fractional Calculus  
Next found the FC regression Analytically solving differential equations is a big pain  
Finding ways to automate the FC regression problem might help in lots of areas.

* First, we need a way to plot the given data and guess its polynomial fit to set a limit on the order of Fractional Regression
* Next write suitable FC differential regression equations and find appropriate parameters  
* Finally solve the equation or plot the solution if the analytical solution is hard or nearly impossible.

Given

![equation](https://latex.codecogs.com/png.latex?%5Clarge%20f%20%5Cin%20%5Cmathbb%7BC%7D%5E%7Bn%7D%5Ba%2Cb%5D%20%2C%20%5Calpha%20%5Cin%20%5B0%2C&plus;%5Cinfty%20%5D%20%2C%20n%20%5Cin%20%5Cmathbb%7BN%7D%20%2C%20%5Calpha%20%5Cin%20%28n-1%2Cn%29)

The Caputo fractional derivative of f of order \alpha is

![equation](https://latex.codecogs.com/png.latex?%5CLARGE%20_%7BD%7D%5E%7BC%7D%5Ctextrm%7B%7D_%7B%5Calpha&plus;%7D%5E%7B%5Calpha%20%7D%20f%28x%29%20%3A%3D%20%5Cfrac%7B1%7D%7B%5CGamma%20%7B%28n-1%29%7D%7D%20%5Cint_%7Ba%7D%5E%7Bx%7D%20%28x-t%29%5E%7Bn-%5Calpha-1%7D%20f%5E%7B%28n%29%7D%28t%29%20dt)

Where Gamma function is defined as

![equation](https://latex.codecogs.com/png.latex?%5Clarge%20%5CGamma%20%28x%29%20%3A%3D%20%5Cint_%7B0%7D%5E%7B%5Cinfty%20%7D%20t%5E%7Bx-1%7D%20e%5E%7B-t%7D%20dt%20%2C%20x%20%3E%200)
