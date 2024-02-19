# Sorting_Algorithms

Problem Statement:

Implement a Java program to sort integer data stored in text files using both insertion sort and merge sort algorithms. The program should read the input data from multiple text files, each containing a list of integers represented as triplets of numbers. It should then sort the data by the last column of each triplet using both insertion sort and merge sort algorithms.

Objective:

Develop a program to read integer data from text files and sort it using insertion sort and merge sort algorithms.
Compare the performance of insertion sort and merge sort for different sizes of input data.
Output the sorted data into new text files and measure the execution time of each sorting algorithm.
Functionality:

Read input data from specified text files, with each line representing a triplet of integers separated by spaces.
Implement an insertion sort algorithm to sort the data by the last column of each triplet.
Implement a merge sort algorithm to sort the data by the last column of each triplet.
Output the sorted data into new text files, appending "_O" to the original file name.
Measure and display the execution time of each sorting algorithm for each input file.
Analyze and compare the performance of insertion sort and merge sort based on execution time and input data size.
Constraints:

Input data consists of triplets of integers separated by spaces.
The program should handle cases where the input files are not found or the data is incorrectly formatted.
The program should efficiently handle large input data sizes.
The sorting algorithms should be implemented as separate methods and called appropriately from the main program.
Input Format:

Each input text file contains multiple lines, each representing a triplet of integers separated by spaces.
Output Format:

The program outputs the sorted data into new text files, with names based on the original file names.
It displays the execution time of each sorting algorithm for each input file.
Example:

yaml
Copy code
Input:
File: arr20.txt
Contents:
10 20 30
5 15 25
...
20 40 60

Output:
File: arr20_O.txt
Sorted Contents:
5 15 25
10 20 30
...
20 40 60

Execution Time:
Insertion Sort: 5000 nano seconds
Merge Sort: 2000 nano seconds
Performance Analysis:

Measure the execution time of each sorting algorithm for different input file sizes.
Compare the performance of insertion sort and merge sort based on execution time and input data size.
Analyze the time complexity of both sorting algorithms and their practical efficiency for sorting large datasets.
Note:

Ensure to handle file input/output operations and any potential errors gracefully.
Use appropriate data structures and algorithms to efficiently implement the sorting algorithms and handle large datasets.
