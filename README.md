The file contains the code for the optimisation of the unknown variables

Step1: estimate mising information about corresponding T values, so estimation by calculating how far each was from start point then scaled them
distances to fit in the range of 6 to 60

Step 2: made a scoring system to predict how close predicted curve is close to acutal one. L-BFGS optimatisation to do this(source numericaloptimisation by Jorge nocedadl)
Step 3: wait for the values to converge
