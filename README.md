# Sorting Algorithms

<p align="center"><img src="SortingAlgorithms.gif" width="700"></p>

## Welcome
Here are my implementations of popular sorting algorithms in python. The benefits of Python made it easier, more compact, and faster to code than C. My C sorting algorithms are in a separate GitHub directory.

## Table of Contents
* [About](#about)
* [Requirements](#requirements)
* [Installation](#installation)
* [Usage](#Usage)

## About
This repository contains sorting algorithms for

* [Bubble sort](https://en.wikipedia.org/wiki/Bubble_sort)

* [Heap sort](https://en.wikipedia.org/wiki/Heapsort)

* [Insertion sort](https://en.wikipedia.org/wiki/Insertion_sort)

* [Merge sort](https://en.wikipedia.org/wiki/Merge_sort)

* [Quicksort1 (the traditional way)](https://en.wikipedia.org/wiki/Quicksort)

* [Quicksort2 (using python lists)](https://en.wikipedia.org/wiki/Quicksort)

* [Selection sort](https://en.wikipedia.org/wiki/Selection_sort)

* [Shellsort](https://en.wikipedia.org/wiki/Shellsort)

## Requirements
* Ubuntu 14.04 LTS
* python3 3.4.3
* pycodestyle 2.4.0 (linter - python)
* All programs were run on a Vagrant(ubuntu/trusty64) (Virtualbox) environment

## Installation
In your terminal, git clone the directory with the following command:
```
git clone https://github.com/feliciahsieh/SortingAlgorithms.git
```

## Usage
Type the sorting algorithm you want to run in python. All of the programs measure the time it takes for processing the program using the same list of integers. Currently, each sorting algorithm uses the following as the input.
```
[23, 6, 1, 90, 30, 39, 99, 15, 88, 0]
```

The output will look similar to the following:

<p align="center"><img src="HeapsortExample.png" width="700"></p>

You run each program as follows:

```
./bubblesort.py
./heapsort.py
./insertionsort.py
./mergesort.py
./quicksort1.py
./quickSort2.py
./selectionsort.py
./shellsort.py
```
