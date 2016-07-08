# Recursive Art
![]()

### 1. Introduction
This is a continuation of the project [A Scheme Interpreter].
In the previous project, we've added a number of primitive drawing procedures that are collectively called "turtle graphics". The turtle represents the state of the drawing module, which has a position, an orientation, a pen state (up or down), and a pen colour. The `tscheme__x_` functions in `scheme_primitives.py` are the implementations of these procedures, and show their parameters with a brief description of each.

The Python [documentation of the turtle module] contains more detail.

Idea: Create a visualization of an iterative or recursive process of our choosing, using turtle graphics. Our implementation must be written entirely in Scheme using the interpreter we have built. However, we may add primitive procedures to interface with Python's `turtle` or `math` modules. Other than that all computation must be done in Scheme.

### 2. Files

Files in this project:

* `contest?.scm`: The drawing algorithms

### 3. Running the drawing

First, download the previous project [A Scheme Interpreter]. A copy of all the drawings can also be found under the folder `contest` in the previous project folder. Then move the drawing to the Scheme Interpreter's directory (same directory as `scheme.py`).

Then run the Scheme interpreter in an interactive session:
```sh
$ python3 scheme.py
```

Alter that, load the drawing:
```lisp
scm> (load 'contest)
```

Make sure the name of the drawing file is alphanumeric (containes no spaces nor special characters).

To count the token used in the drawing file:
```sh
$ python3 scheme_tokens.py contest.scm
```


### 4. Class Project Site
[here]

### 6. Extra - the CRAZIES drawing I ve ever seen:


Tail Recursive Ray Tracer (T.R.R.T) [43.scm (1857 tokens)]
![](http://inst.eecs.berkeley.edu/~cs61a/fa13/proj/scheme_contest_gallery/43.png)

[here]: <http://61a-su15-website.github.io/proj/scheme_contest/>
[A Scheme Interpreter]: <https://github.com/timkchan/scheme>
[documentation of the turtle module]: <https://docs.python.org/release/3.2/library/turtle.html>
[43.scm (1857 tokens)]: <http://inst.eecs.berkeley.edu/~cs61a/fa13/proj/scheme_contest_gallery/43.scm>