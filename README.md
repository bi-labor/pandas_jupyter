# Business Intelligence - Pandas

# Installation

All packages are preinstalled on the lab computers but you are free to use your own notebook.
The [Anaconda](https://www.anaconda.com/distribution/#download-section) Distribution contains all packages necessary for this lab.
You can also install the packages one by one via pip or conda, you'll need:

    conda install jupyter pandas numpy sklearn seaborn matplotlib

or via pip:

    pip install jupyter pandas numpy sklearn seaborn matplotlib

Additionally I recommend using the Table of Contents notebook extension.

[Nbextensions](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html)
[Table of contents](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/toc2/README.html)

A Pandas intro is available [here](https://github.com/bi-labor/pandas_jupyter/blob/master/notebooks/Pandas_alapok.ipynb) (Hungarian).

The problem file that you need to turn in is located [here](https://github.com/bi-labor/pandas_jupyter/blob/master/notebooks/pandas_labor_2020.ipynb).

# General information

(this is copied from the notebook)

This goal of this notebook is to give a brief introduction to the `pandas` library, a popular data manipulation and analysis tool for Python.

Problems are numbered from **Q1** to **Q5** with many subproblems such as **Q1.1**. The scores range from 2 to 5 based on the difficulty of the problem. Grades are determined using this table (TODO update):

| score | grade |
| ---- | ----|
| 80+ | 5 |
| 60+ | 4 |
| 40+ | 3 |
| 20+ | 2 |
| 20- | 1 |

Your answer should go in place of `YOUR CODE HERE`. Please remove `raise NotImplementedError`.
Most of the tasks are automatically graded using visible and hidden tests.
Visible tests are available in this version, hidden tests are not available to you.
This means that passing all visible tests does not ensure that your answer is correct.
Not passing the visible tests means that your answer is incorrect.
Do not delete or copy cells and do not edit the source code.
You may add cells but they will not be graded.
You will not find the hidden tests in the source code but you can mess up the autograder if you manually edit it.

Advanced exercises are marked with \*.
More advanced ones have more stars.
Some problems build on each other - it should be obvious how from the code - but advanced problems can safely be skipped.
Completing all non-advanced exercises correctly is worth 63 points.

### Submission

You only need to submit this notebook (no separate report).
Make sure that you save the last version of your notebook.
Please rename the notebook to your neptun code (`ABC123.ipynb`), package it in an archive (`.zip`) and upload it to the class website.
You are free to continue working on this problem set after class but make sure that you upload it by the end of the week (Sunday).

**VERY IMPORTANT** Run Kernel->Restart & Run All and make sure that it finishes without errors.
If you skip exercises, you need to manually run the remaining cells.
Skipping exercises won't affect the autograder.


### Tips

You generally don't need to leave any DataFrames printed as cell outputs. You can do it for debug purposes and it won't affect the autograder but please don't leave long tables in the output. Use `.head()` instead.

Be concise. All exercises can be solved with less than 5 lines of code.

Avoid overriding Python built-in functions with your own variables (`max = 2`).

If you mess up, you can always do one of the following
  1. Kernel -> Restart & Run All - this will run all cells from top to bottom until an exception is thrown
  1. Kernel -> Restart, Cell -> Run All Above - this will run all cells from top to bottom until the current cell is reached or and exception is thrown

If your notebook runs for longer than a minute, one or more of your solutions is very inefficient.

### Feedback

Please fill out this [short survey](https://forms.gle/i717e8Mzijjy3Pfk9) after you completed the problems.
