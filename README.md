# Gauss-Seidel-Power-Flow-Analysis

ALGORITHM
--------

STEP 1  : Read the input data.
STEP 2  : Find the admittance matrix
STEP 3  : Choose the flat voltage profile 1+j0 to all buses except slack bus.
STEP 4  : Set the iteration count p=0 and bus count i=1.
STEP 5  : Check the slack bus, if it is the generator bus then go to the next step otherwise go to step 7.
STEP 6  : Before the check for slack bus, if it is slack bus then go to step 11 otherwise go to the next step. 
STEP 7  : Check the reactive power of the generator bus within the given limit.
STEP 8  : If the reactive power violates the limit treat the bus as a load bus.
STEP 9  : Calcuate the phase of the bus voltage on load bus.
STEP 10 : Calculate the change in bus voltage of the repeat step mentioned above until all the bus voltages are calculated. 
STEP 11 : Stop the program and print the results.
