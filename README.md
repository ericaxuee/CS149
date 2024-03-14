# CS149 Assignment #3
# Description:
* This C program will go through zero or more files of names and print every unique name along with its number of occurrences in a parallel fashion using multiple processes.

# Author names:
* Prathyush Jonnalagadda and Erica Xue 
## Author emails:
* prathyush.jonnalagadda@sjsu.edu and erica.xue@sjsu.edu

# Last modified date: 3/13/2024

# Creation date: 3/7/2024

# Running the code:
* First compile using command "gcc -o countnames_parallel countnames_parallel.c -Wall -Werror"
* Once the executable countnames is obtained, cd to its parents directory
* Run the following commands which execute the program with the test files in the same directory:
* ./countnames_parallel names1.txt names2.txt
* ./countnames_parallel names1.txt names2.txt names2.txt
* time ./countnames_parallel names1.txt names2.txt

## Runtime results
* ./countnames_parallel names1.txt names2.txt  0.00s user 0.00s system 2% cpu 0.182 total
* ./countnames_parallel names1.txt names2.txt  0.00s user 0.00s system 79% cpu 0.006 total
* ./countnames_parallel names1.txt names2.txt  0.00s user 0.00s system 77% cpu 0.007 total
* ./countnames_parallel names1.txt names2.txt  0.00s user 0.00s system 81% cpu 0.006 total
* ./countnames_parallel names1.txt names2.txt  0.00s user 0.00s system 81% cpu 0.006 total

* Average runtime: 0.00s user 0.00s system 64% cpu 0.0414 total
