# DSCI 512: Algorithms and Data Structures

How to choose and use appropriate algorithms and data structures to help solve data science problems. Key concepts such as algorithmic complexity and recursion.

## License

© 2022 Mike Gelbart & Arman Seyed-Ahmadi

Software licensed under [the MIT License](https://spdx.org/licenses/MIT.html), non-software content licensed under [the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) License](https://creativecommons.org/licenses/by-nc-sa/4.0/). See the [license file](LICENSE.md) for more information.

## Lectures

Find Panopto lecture recordings [here](https://ubc.ca.panopto.com/Panopto/Pages/Sessions/List.aspx?folderID=40ecc7b1-100e-4984-815c-af0101037194).

| # | Topic | Optional supplementary material |
|---|-------|---------------------------------|
| 1 | Time complexity, big O, space complexity [[lecture](lectures/01_complexity-big-O.ipynb), [activity](activities/a01_complexity-big-O.ipynb)] | [Introduction to Big O notation](https://www.youtube.com/watch?v=D6xkbGLQesk), [Runestone](https://runestone.academy/runestone/books/published/pythonds/index.html) Chapter 3 |
| 2 | Searching, sorting, hash tables [[lecture](lectures/02_searching-sorting-hash.ipynb), [activity](activities/a02_searching-sorting-hash.ipynb)] | [Binary search video](https://youtu.be/y62zj9ozPOM?t=1314), watch until 31:00 (9 min), notes on [Profiling and Timing Code](https://jakevdp.github.io/PythonDataScienceHandbook/01.07-timing-and-profiling.html), [Runestone](https://runestone.academy/runestone/books/published/pythonds/index.html) Chapter 6.1-6.8 |
| 3 | Recursive algorithms [[lecture](lectures/03_recursive-algorithms.ipynb), [activity](activities/a03_recursive-algorithms.ipynb)] | [Runestone](https://runestone.academy/runestone/books/published/pythonds/index.html) Chapter 5 |
| 4 | Recursive data structures [[lecture](lectures/04_recursive-data-structures.ipynb), [activity](activities/a04_recursive-data-structures.ipynb)] | [Runestone](https://runestone.academy/runestone/books/published/pythonds/index.html) Chapter 7 |
| 5 | Graphs, graph searches [[lecture](lectures/05_graphs.ipynb), [activity](activities/a05_graphs.ipynb)] | [NetworkX tutorial](https://networkx.github.io/documentation/stable/tutorial.html), [AIspace graph searches](http://aispace.org/search/index.shtml), [Graph traversals video](https://www.youtube.com/watch?v=bIA8HEEUxZI); brilliant.org on [Graph Theory](https://brilliant.org/wiki/graph-theory/), [Traversals](https://brilliant.org/wiki/traversals/), and [BSTs](https://brilliant.org/wiki/binary-search-trees/), [Runestone](https://runestone.academy/runestone/books/published/pythonds/index.html) Chapter 8 |
| 6 | Sparse matrices [[lecture](lectures/06_sparse-matrices.ipynb), [activity](activities/a06_sparse-matrices.ipynb)] |  |
| 7 | Discrete optimization & scheduling [[lecture](lectures/07_discrete-optimization.ipynb), [activity](activities/a07_discrete-optimization.ipynb)] | [Linear programming and discrete optimization with Python using PuLP](https://towardsdatascience.com/linear-programming-and-discrete-optimization-with-python-using-pulp-449f3c5f6e99)  |
| 8 | Dynamic programming, code vectorization [[lecture](lectures/08_dynamic-programming-vectorization.ipynb), no activity] | [Dynamic programming](http://web.mit.edu/15.053/www/AMP-Chapter-11.pdf) |

## Lab Assignments

There will be one lab assignment per week. We will follow the standard MDS lab deadlines.

## Quizzes

Quizzes will be **open book**, meaning you may consult course materials, online sources, Python, etc. However, communication with other people during the quiz is strictly forbidden. See the MDS quiz instructions [here](https://ubc-mds.github.io/resources_pages/quiz/). For the dates/times of the quizzes, see the [MDS calendar](https://ubc-mds.github.io/calendar/).

## Installation

The course's conda environment file is [here](https://github.ubc.ca/MDS-2022-23/DSCI_512_alg-data-struct_students/blob/master/dsci512env.yml). To create the environment: `conda env create -f dsci512env.yml` (you only need to do this once). To activate the environment: `conda activate dsci512env` (you need this for each new terminal window). In short, run `conda install -c conda-forge nb_conda_kernels` in your **base** environment (this only has to be done once across all courses, so you may have done it already), then launch Jupyter Lab from your **base** environment, and finally select the `dsci512env` kernel from within Jupyter.

## Course Learning Objectives

By the end of the course, students are expected to be able to:

1. Analyze the scalability and trade-offs of various basic algorithms and data structures using Big-O notation.
2. Read and interpret recursive functions.
3. Select appropriate data structures, such as graphs, given a data set. 
4. Map certain real-world problems to discrete optimization problems.
5. Diagnose rate-limiting aspects of slow Python code and enumerate various options for speeding it up.

## Online reference material

- [Problem Solving with Algorithms and Data Structures using Python](https://runestone.academy/runestone/books/published/pythonds/index.html)
- [Visualizing Algorithms](https://bost.ocks.org/mike/algorithms/)
- [500 Data Structures and Algorithms practice problems and their solutions](https://techiedelight.quora.com/500-Data-Structures-and-Algorithms-interview-questions-and-their-solutions)
- [Recursion practice problems](https://www.w3resource.com/python-exercises/data-structures-and-algorithms/python-recursion.php)
- [P vs. NP and the Computational Complexity Zoo](https://www.youtube.com/watch?v=YX40hbAHx3s) (video)

## Books

- Goodrich, Tamassia, Goldwasser. [Data Structures and Algorithms in Python](https://www.amazon.ca/Structures-Algorithms-Python-Michael-Goodrich/dp/1118290275/).
- Sanjoy Dasgupta, Christos  Papadimitriou and Umesh Vazirani, *Algorithms*, available [here](https://book.huihoo.com/pdf/algorithms/).

# Attribution

The content of this course was mainly developed by [Mike Gelbart](https://www.mikegelbart.com/), with minor modifications and updates made by Arman Seyed-Ahmadi during the 2022 offering of the course.
