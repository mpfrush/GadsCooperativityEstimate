# GadsCooperativityEstimate

## Program for estimation of Gads binding cooperativity to LAT peptide. 

The program uses the multivariate Ordinary Least Square (OLS) to estimate kinetic parameters for the reaction network. 
OLS minimizes the Residual Sum of Squares (RSS) between the observed responses and the responses predicted by solving the set of Ordinary
Differential Equations (ODEs) for the reaction network. It uses quasi-Newton method L-BFGS (Limited-memory Broyden-Fletcher-Goldfarb-Shanno) algorithm to optimize the RSS and kinetic parameters. The program is written in Python 2.7. 




Files: 

1. A description of the computational model is in Comp Model.pdf file
2. GadsCooperativityEstimateProgram.ipynb is Python code
   GadsCooperativityEstimateProgram.pdf is PDF printed code
   GadsCooperativityEstimateProgram.html is HTML version of code
