# mp_spec
## Codes for "Monetary Policy and Speculative Stock Markets"

The full paper can be found on my website: [gregorboehl.com](gregorboehl.com)

The simulation code is written in Python. Although I used Python version 3.6.4 the code should be backwards compatible and also run under Python 2.7 (not tested).

The *.py files are the following:
  
   * base.py: definitions of functions used by other files.
   * bif.py}: bifurcation diagrams for phi_s, alpha and gamma (Figure 2 and Figures in Appendix D). Chose in the first paragraph of the code which diagram to plot.
   * coef.py: code for Figure 1.
   * msm.py: code for method of simulated moments. Chose in the first paragraph of the code which model to estimate (with or without exogenous shocks to stock prices, with or without behavioral speculation).
   * vars.py: code for Figure 3.

Additionally I provide the three data files (*.xls and *.csv) containing the data as described in the paper.

The code is modified such that you can run it directly from within a folder that contains all the files, i.e. via command line: 

E.g: `python coef.py`

