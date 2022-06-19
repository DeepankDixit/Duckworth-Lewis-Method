Assignment 1: Duckworth Lewis Method

Here's the data file you will use:

ODI over-by-over data (https://ece.iisc.ac.in/~rajeshs/E0259/04_cricket_1999to2011.csv) (.csv file):

This file contains data on ODI matches from 1999 to 2011. It is taken from this site. There is an R code for finding the 'run production functions' in this site, but you will do something marginally different in the following assignment.
Discussion is encouraged. But write your own code. Please comply with the ethics policy. You must sign the submission statement and click the submit button to submit your work.

Using the first innings data alone in the above data set, find the best fit 'run production functions' in terms of wickets-in-hand w and overs-to-go u. Assume the model Z(u,w) = Z0(w)[1 - exp{-Lu/Z0(w)}]. Use the sum of squared errors loss function, summed across overs, wickets, and data points.

Note that your regression forces all slopes to be equal at u = 0. You should provide a plot of the ten functions, and report the (11) parameters associated with the (10) production functions, and the normalised squared error (total squared error summed across overs, wickets, and data points, and normalised by the number of data points) in your pdf file.

Feel free to use tools for nonlinear regression available in Python. Some date fields are in different format with an extra comma. Write a short script to clean this up. This clean-up code should a part of the main program. You may create a temporary data file, but remove the temporary data file after the output data has been generated.
