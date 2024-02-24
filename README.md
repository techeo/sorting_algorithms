# Sorting Algorithms & Big O

This project implements various sorting algorithms in C.

## Tests :heavy_check_mark:

* [Tests](./tests): Includes test files. 

## Helper Files :raised_hands:

* [print_array.c](./print_array.c): Function to print an array of integers. 
* [print_list.c](./print_list.c): Function to print a doubly-linked list.

## Header Files :file_folder:

* [sort.h](./sort.h): Header file with definitions and prototypes.

Data Structures:

```
typedef struct listint_s
{
	const int n;
	struct listint_s *prev;
	struct listint_s *next;
} listint_t;
```

Function Prototypes:

- See [sort.h](./sort.h)

## Tasks :page_with_curl:

* **Bubble sort**
  * Sorts an array of integers using the Bubble Sort algorithm.
  * [0-bubble_sort.c](./0-bubble_sort.c)

* **Insertion sort**
  * Sorts a doubly-linked list of integers using the Insertion Sort algorithm.
  * [1-insertion_sort_list.c](./1-insertion_sort_list.c)

* **Selection sort**
  * Sorts an array of integers using the Selection Sort algorithm.
  * [2-selection_sort.c](./2-selection_sort.c)

* **Quick sort**
  * Sorts an array of integers using the Quick Sort algorithm (Lomuto partition scheme).
  * [3-quick_sort.c](./3-quick_sort.c)

* **Shell sort - Knuth Sequence**
  * Sorts an array of integers using the Shell sort algorithm.
  * [100-shell_sort.c](./100-shell_sort.c)

* **Cocktail shaker sort**
  * Sorts a doubly-linked list of integers using the Cocktail Shaker Sort algorithm.
  * [101-cocktail_sort_list.c](./101-cocktail_sort_list.c)

* **Counting sort**
  * Sorts an array of integers using the Counting Sort algorithm.
  * [102-counting_sort.c](./102-counting_sort.c)

* **Merge sort**
  * Sorts an array of integers using the Merge Sort algorithm.
  * [103-merge_sort.c](./103-merge_sort.c)

* **Heap sort**
  * Sorts an array of integers using the Heap Sort algorithm.
  * [104-heap_sort.c](./104-heap_sort.c)

* **Radix sort**
  * Sorts an array of integers using the Radix Sort algorithm.
  * [105-radix_sort.c](./105-radix_sort.c)

* **Bitonic sort**
  * Sorts an array of integers using the Bitonic Sort algorithm.
  * [106-bitonic_sort.c](./106-bitonic_sort.c)

* **Quick Sort - Hoare Partition scheme**
  * Sorts an array of integers using the Quick Sort algorithm (Hoare partition scheme).
  * [107-quick_sort_hoare.c](./107-quick_sort_hoare.c)

* **Dealer**
  * Sorts a doubly-linked list deck of cards.
  * [1000-sort_deck.c](./1000-sort_deck.c)
