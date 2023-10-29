# AIM
Sorting-Algorithm
i) Selection Sort  ii) Insertion Sort   iii) Bubble Sort

# THEORY

A Sorting Algorithm is used to rearrange a given array or list of elements according to a comparison operator on the elements. The comparison operator is used to decide the new order of elements in the respective data structure.

Selection Sort
In selection sorting technique, the smallest element is fetched by comparing itself with the rest of the elements and sorted at the array's first position. The complete array is divided into two halves, the sorted subarray on the left and the unsorted subarray on the right. Once the first element is sorted, the search for the second minimum element begins from the rest of the array and is positioned at second place.
Similarly, all the elements are positioned on the sorted side of the subarray one after the other, and the complete array becomes a sorted array.

Insertion Sort
In this sorting technique, the elements are sorted by comparing the elements with their previous elements. It starts by comparing the second element with the first element. If the second element is smaller than the first, then we will swap it.
After that, we will compare the third element with all the elements that are before it. Similarly, it goes for the fourth element and so on. Once all the comparisons are made, the elements become sorted.

Bubble Sort
Bubble sort is one of the most straightforward sorting algorithms. In this sorting technique, we begin by comparing the first two elements of the array and checking if the first element is greater than the second element; if it is, we will swap those elements and move forward to the next element.
If the first element is not greater than the second, then we don’t need to swap it. And this process will keep on repeating till the end of the array.

# ALGORITHM

Here's the algorithm for the provided C++ program that sorts an array using Selection Sort, Insertion Sort, or Bubble Sort based on user input:

1.Start

2.Declare an integer variable n to store the number of elements in the array.

Output "Enter the number of elements in the array: " to prompt the user for input.

Read the value of n from the user.

3.Declare an integer array arr of size n to store the elements of the array.

Output "Enter n elements of the array: " to prompt the user for the array elements.

Use a loop to read and store the n elements in the arr array.

4.Declare an integer variable choice to store the user's choice of sorting algorithm.

Output "Choose a sorting algorithm:".

Output "1. Selection Sort".

Output "2. Insertion Sort".

Output "3. Bubble Sort".

Output "Enter your choice: " to prompt the user for their choice.

5.Read the value of choice from the user.

6.Use a switch statement to perform the selected sorting algorithm based on the value of choice:

a. If choice is 1, call the selectionSort(arr, n) function to perform Selection Sort.

b. If choice is 2, call the insertionSort(arr, n) function to perform Insertion Sort.

c. If choice is 3, call the bubbleSort(arr, n) function to perform Bubble Sort.

d. If choice is none of the above, output "Invalid choice" and return 1 to exit the program.

Output "Sorted array: " to indicate the sorted array.

7.Use a loop to display the elements of the sorted arr array.

8.End

The program provides the user with a menu to choose a sorting algorithm and then displays the sorted array using the selected sorting technique.

# OUTPUT

1.

![image](https://github.com/Sanika-Desai/Sorting/assets/142314095/ca7759fd-fd1d-4aca-b305-0686c27d146e)

2.

![image](https://github.com/Sanika-Desai/Sorting/assets/142314095/314781b7-2a47-48cf-9d54-e19a47c5cedc)

3.

![image](https://github.com/Sanika-Desai/Sorting/assets/142314095/dba84799-fdda-4005-86b3-6bfbc5f4a7eb)

4.

![image](https://github.com/Sanika-Desai/Sorting/assets/142314095/eab47bcc-cd47-4a56-9807-2435ceaf735e)

![image](https://github.com/Sanika-Desai/Sorting/assets/142314095/0d7cce5b-84d1-4d00-825a-893ce002d080)

![image](https://github.com/Sanika-Desai/Sorting/assets/142314095/f972591d-191d-4df0-aef2-ee420f4a1094)

