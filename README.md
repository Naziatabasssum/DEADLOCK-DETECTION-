# DEADLOCK-DETECTION-
ALGORITHM:

1. Mark each process that has a row in the Allocation matrix of all zeros.
2. Initialize a temporary vectorW to equal the Available vector.
3. Find an indexi such that processi is currently unmarked and thei th row ofQ
is less than or equal to W . That is,Q ik … Wk, for 1 … k … m . If no such row is
found, terminate the algorithm.
4. If such a row is found, mark processi and add the corresponding row of the
allocation matrix to W . That is, setWk = Wk + Aik, for 1 … k … m . Return
to step 3.

OUTPUT:

Enter the no of process: 4
Enter the no of resources: 5

Total Amount of the Resource R1: 2
Total Amount of the Resource R2: 1
Total Amount of the Resource R3: 1
Total Amount of the Resource R4: 2
Total Amount of the Resource R5: 1

Enter the request matrix:0 1 0 0 1
0 0 1 0 1
0 0 0 0 1
1 0 1 0 1

Enter the allocation matrix:1 0 1 1 0
1 1 0 0 0
0 0 0 1 0
0 0 0 0 0

 Deadlock detected
--------------------------------
