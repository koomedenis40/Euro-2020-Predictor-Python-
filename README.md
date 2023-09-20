## Euro-2020-Pythin- Predictor-Python
### This is a Python code for the Euro-2020-Predictor Program

This repository contains the code used to win the Royal Statistical Society's Euro 2020 Prediction Competition.
The main code can be found in the file "Euro 2020 Predictions - Getting Started.ipynb".

The code is based on a simple double Poisson model, where each team A is given an attacking strength O_A 
and a defensive vulnerability V_A. Then, the goals scored by team A against team B are assumed to be Poisson 
distributed with mean O_A * V_B.

While the code is currently set up to predict Euro 2020, changing it to work for another
football tournament is simple. One needs a CSV file containing previous results between the tournament teams and another containing the matches that need to be predicted. 
These files should mimic the format of the two CSV files contained in this repository.

## Note
The results.csv file was taken from 
https://www.kaggle.com/martj42/international-football-results-from-1872-to-2017
to help work on this project. 
