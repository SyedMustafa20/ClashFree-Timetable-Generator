# ClashFree-Timetable-Generator
A genetic algorithm that generates a clash-free timetable. This algorithm utilizes concepts including tournament selection, heuristics, mutation and 2-point crossovers for generation of fittest chromosomes.
# For Generic Cod
The attached code is hardcoded for varaibales initialized at the start of the code.
To modify the code to work for any set of values, you are required to declare variables containing the max values of your constraints in binary.
After initialization, instead of dissecting chromosomes direclty using index values (hard coding), use variables.
For example if val1 is occupies 3 indexes in the chromosome followed by val2 that occupies 4 indexes. To access the 6th index, insetead of writing chromosome[6], use chromosome[val1+3]. So that when the max size of val1 changes, the indexes and calculations are accomodated accordingly in the chromosome.
# Exit Conditions
For accurate results, search and assign optimal number of chromosomes for tournament selection.
Also update the "iterations without any change in chromosomes" according to your choice for example, you may set its value to be 50, 100 etc.
