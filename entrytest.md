Python Basic Programming -- 1.0b-- README.md

Python Basic Programming test 1.0 beta
======================================

Bart Gerritsen
--------------

Project Description
-------------------
The Python Basic Programming project is a TU Delft DigitalSkills' project to
developed and distribute Python programming interactive learning materials for
year 1 students. In response to the widely varying level of programming skills
of incoming students, an *Entry Test* will be made available, that will guide
students in their choice for the best fitting entry point into these materials.

Content repository
---------------
This repository contains 4 Jupyter Notebooks, with images, and other support
materials, comprising the 4 main topics to be tested in the Entry Test. see below table.

|Notebook|Covers|Content|Grading|
|:---|:---|:---|:---|
|`entry_test_basic_20`|Variables|5 exercises: create, (re)assign, print, operate upon, convert, ...) numeric, boolean, and Sequence type variables| auto-graded|
|`entry_test_basic_40`|Control Flow|5 exercises: if-the-else, loops, logical expressions, negate, predicates|auto-graded|
|`entry_test_basic_60`|Source Code Organization|5 exercises: indentation, import, execution flow, functions| auto-graded|
|`entry_test_basic_80`|Basic Plotting [1]|5 exercises: plot functions in 1 variable, scatter plots, vector, histograms| auto-graded|

[1] In this course, plotting uses `Matplotlib.pyplot`

Collectively, these tests make up the Entry Test for Python Basic Programming for the 2019-2020 TU Delft Curriculum.  

What to do?
-----------
- get the tests on Gitlab of EEMCS
- install them locally keeping the directory structure as in here
- open an Anaconda Prompt (Terminal), navigate to your notebook folder and
  from within the Anaconda prompt launch Jupyter Notebooks, like so:
  ```bash
  [d:] cd /my_path/to_the_entry_test/
  [d:] jupyter notebook
  ```
  A web interface opens in your browser, with a file overview showing the
  content of the current directory, with the entry test notebooks
- open the notebook by clicking it and start working on the test
- make notes of every issue you encounter; see the Work Plan we sent you for
  aspects and issues to observe

Below is a snapshot to illustrate.

![entry_test_basec_20](./figures/nb-1.png)
Each Notebook starts with instructions. Carefully read these Instructions in the Notebook.

![entry_test_basec_20](./figures/nb-2.png)
Always:
- in the code box where your code is expected remove or comment out this part:

```Python
# YOUR CODE HERE
raise NotImplementedError
```

and insert your code. In this exampple, the code requested is just: `option=1`, So the content of the code box of Exercise 1 becomes:

```Python
# YOUR CODE HERE
# raise NotImplementedError
option = 1
```

Whitespace is insignificant.

Remark: you often see empty boxes you cannot enter. Ugly, but ignore them. They are for auto-grading. Always put your answer in the single code box that contains a code skeleton, and on the position where it says `# YOUR CODE HERE`


What is needed for the test?
----------------------------
1. TU Delft Anaconda installation of Python (which includes Jupyter Notebook); get it on: [software.tudelft.nl](http://software.tudelft.nl)

Inquiries and contact
---------------------
Questions can be submitted to: Bart Gerritsen

b.h.m.gerritsen@tudelft.nl

References
----------
1. [Project Jupyter (Jupyter.org)](https://jupyter.org/)
2. [Jupyter Notebook Tutorial: The Definitive Guide (DataCamp)](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook?utm_source=adwords_ppc&utm_campaignid=898687156&utm_adgroupid=48947256715&utm_device=c&utm_keyword=&utm_matchtype=b&utm_network=g&utm_adpostion=1t1&utm_creative=332602034352&utm_targetid=dsa-473406581035&utm_loc_interest_ms=&utm_loc_physical_ms=1010704&gclid=EAIaIQobChMIu5ST4qXp4wIVUOJ3Ch06cQ5REAAYASAAEgKNt_D_BwE)
3. [Jupyter Notebook for Beginners: A Tutorial (DataQuest)](https://www.dataquest.io/blog/jupyter-notebook-tutorial/)
4. [Jupyter Notebook: An Introduction (RealPython)](https://realpython.com/jupyter-notebook-introduction/)
