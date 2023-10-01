# ls-py-dyna
A Python library to process FE Simulation software LS-DYNA input and results file.

# Functionality

1. Read a LS-DYNA input file and parse through all the keyword cards defined in the file. In case the LS-DYNA input file has *INCLUDE 
keyword card with a path to another LS-DYNA file, then read that content of all such include files.
