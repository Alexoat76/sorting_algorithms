![Brand](https://assets.website-files.com/6105315644a26f77912a1ada/610540e8b4cd6969794fe673_Holberton_School_logo-04-04.svg)

# 0x1B. C - Sorting algorithms & Big O
<div style="text-align: justify">
	
In this project, you should be to practice to how to use implement different sorting algorithms. </div>
<div style="text-align: justify">
Don't forget to fully meet the following development requirements. </div>


# Getting Started :running:

## Table of Contents :clipboard:

* [Requirements](#requirements-page_with_curl)
* [Files](#files-file_folder)
* [Tasks](#tasks-page_with_curl)
* [Credits](#credits)

## Requirements :page_with_curl:

### Resources

**Read or watch** :

[![M](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Google_2015_logo.svg/80px-Google_2015_logo.svg.png)](https://www.google.com/search?q=big+o+notation&oq=big+o+&aqs=chrome.1.69i57j0i512l3j0i457i512j0i512j46i175i199i512j0i512l2j46i512.4534j0j15&sourceid=chrome&ie=UTF-8)

[![M](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Logo_of_YouTube_%282015-2017%29.svg/70px-Logo_of_YouTube_%282015-2017%29.svg.png)](https://www.youtube.com/results?search_query=big+o+notation)

<div style="text-align: justify">
	
[Sorting algorithm](https://en.wikipedia.org/wiki/Sorting_algorithm)</div>
<div style="text-align: justify">
	
[Big O notation](https://stackoverflow.com/questions/487258/what-is-a-plain-english-explanation-of-big-o-notation)</div>
<div style="text-align: justify">
	
[Sorting algorithms animations](https://www.toptal.com/developers/sorting-algorithms)</div>

[15 sorting algorithms in 6 minutes](https://www.youtube.com/watch?v=kPRA0W1kECg)(WARNING: The following video can trigger seizure/epilepsy. It is not required for the project, as it is only a funny visualization of different sorting algorithms)

## General :page_with_curl:
<div style="text-align: justify">
* Allowed editors: vi, vim, emacs. </div>
<div style="text-align: justify">
* All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options: 
	
`-Wall -Werror -Wextra -pedantic -std=gnu89`. </div>
<div style="text-align: justify">
* All your files should end with a new line. </div>
<div style="text-align: justify">
	
*A `README.md` file, at the root of the folder of the project is mandatory. </div>

<div style="text-align: justify">
* Your code should use the Betty. It will be checked using</div>

`betty-style.pl` and `betty-doc.pl`.</div>

Please visit the [Betty style](https://github.com/holbertonschool/Betty/wiki) for the full specifications of Betty coding and documentation styles.

<div style="text-align: justify">
* You are not allowed to use global variables. </div>
<div style="text-align: justify">
* No more than 5 functions per file. </div>

<div style="text-align: justify">
	
*You are allowed to use the C standard library. 

<div style="text-align: justify">
*The prototypes of all your functions should be included in your header file called </div>

<div style="text-align: justify"> 

`hash_tables.h` </div>

<div style="text-align: justify">
	
*Don’t forget to push your `header file`.</div>
<div style="text-align: justify">
* All your header files should be include guarded. </div>
<div style="text-align: justify">
	
## Files :file_folder:

* [sort.h](sort.h): Header file containing definitions and prototypes for all types
and functions written for this project.

| File                       | Prototype                                         |
| -------------------------- | ------------------------------------------------- |
| `print_array.c`            | `void print_array(const int *array, size_t size)` |
| `print_list.c`             | `void print_list(const listint_t *list)`          |
| `0-bubble_sort.c`          | `void bubble_sort(int *array, size_t size);`      |
| `1-insertion_sort_list.c`  | `void insertion_sort_list(listint_t **list);`     |
| `2-selection-sort.c`       | `void selection_sort(int *array, size_t size);`   |
| `3-quick_sort.c`           | `void quick_sort(int *array, size_t size);`       |


## Tests :heavy_check_mark:

* [tests](./tests): Folder of test files. Provided by Holberton School.

	
## Tasks :page_with_curl:

* **0. Bubble sort**
  * [0-bubble_sort.c](./0-bubble_sort.c): C function that sorts an array of integers
	  in ascending order using the Bubble Sort algorithm.
		  * Prints the array after each swap.
			  * [0-O](./0-O): Text file containing the best, average, and worst case time
				  complexities of the Bubble Sort algorithm, one per line.

* **1. Insertion sort**
  * [1-insertion_sort_list.c](./1-insertion_sort_list.c): C function that sorts a
	  `listint_t` doubly-linked list of integers in ascending order using the
		  Insertion Sort algorithm.
			  * Prints the list after each swap.
				  * [1-O](./1-O): Text file containing the best, average, and worst case time
					  complexities of the Insertion Sort algorithm, one per line.

* **2. Selection sort**
  * [2-selection_sort.c](./2-selection_sort.c): C function that sorts an array of
	  integers in ascending order using the Selection Sort algorithm.
		  * Prints the array after each swap.
			  * [2-O](./2-O): Text file containing the best, average, and worst case time
				  complexities of the Selection Sort algorithm, one per line.

* **3. Quick sort**
  * [3-quick_sort.c](./3-quick_sort.c): C function that sorts an array of
	  integers in ascending order using the Quick Sort algorithm.
		  * Implements the Lomuto partition scheme.
			  * Always uses the last element of the partition being sorted as the pivot.
				  * Prints the array after each swap.
					  * [3-O](./3-O): Text file containing the best, average, and worst case time
						  complexities of the Quick Sort Lomuto Partition scheme algorithm, one per line.
 
	
## Credits

## Author(s):blue_book:

Work is owned and maintained by 
	**`Alex Orland Arévalo Tribaldos`**  and credits for `group projects` are displayed in the respective `README.md` files.

<3915@holbertonschool.com>
	
[![M](https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Octicons-mark-github.svg/25px-Octicons-mark-github.svg.png)](https://github.com/Alexoat76)
[![M](https://upload.wikimedia.org/wikipedia/fr/thumb/c/c8/Twitter_Bird.svg/25px-Twitter_Bird.svg.png)](https://twitter.com/aoarevalot)
[![M](https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/25px-LinkedIn_logo_initials.png)](https://www.linkedin.com/in/Alexoat76/)


## Acknowledgments :mega: 

### **`Holberton School`** (*providing guidance*)
	
This program was written as part of the curriculum for Holberton School.
Holberton School is a campus-based full-stack software engineering program
that prepares students for careers in the tech industry using project-based
peer learning. For more information,  please visit [this link](https://www.holbertonschool.com/).
