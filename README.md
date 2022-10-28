# PHYS-222-Comp-Phys-Fall-2021
Fall 2021 semester if PHYS 222 Introduction to Computational Physics and Programming.

This repository includes the lab guides developed for PHYS 225 Introduction to Computational Physics and Programming at Rochester Institute of Technology. These activities were most recently used in Fall 2021, but earlier versions have been used between 2017 and 2021. 

## Audience: 
PHYS 222 is a required course for physics majors at RIT, unless they replace it with CS1 and CS2. Typically PHYS 225 is taken in the fall of 2nd year, so earlier in the physics program. All students have had University Physics 1 (Mechanics) before taking PHYS 225, howver some students are concurrently enrolled in University Physics 1 (Electricity and Magnetism). 

The overall philosophy of each activity is to introduce students to: 
* Foundational programming constructs (e.g., lists, loops, conditional statements, functions)
* A familiar physics context from introductory physics. 
* Specific computational skills that are commonly used in physics (e.g., plotting, using physical constants, numerical integration)

The course also has other unique features: 
* Pair programming is used for the 18 structured labs. Pair programming works best when students at a similar level work together. Also, the level of interaction and discussion between partners is substantially better with pair programming because the partners move through the activity at the same pace. 
* A 5 week final project ends the semester with presentations in lieu of a final exam. 

## Unique features

* The activities are provided as Jupyter notebooks. Jupyter notebooks allow students to include theoretical calculations, executable Python code for data analysis, text description, LaTeX equations, and images. The ability to freely blend modeling, data anlaysis and descriptions is a major benefit. 
* Since 2019, the lab activities are provided to students through a JupyterHub server where students access their own copy of the lab guide and submit it. The cells have addition metadata for the [nbgrader package](https://nbgrader.readthedocs.io/en/stable/).  Nbgrader streamlines the distribution, submission, collection, and grading of Jupyter notebooks, and it is very efficient on a JupyterHub server.  
    * Every assignment (PS1A, PS1B, ....) contains a mix of automatically graded and manually graded tasks. The test cases are visible to students, so they keep checking their results until they get it right. 
    * You can learn more about configuring a JupyterHub server though a [wiki tutorial and videos](https://wiki.rit.edu/display/JupyterForTeaching/JupyterHub+Tutorial).
 * Instructors may request copies of the activities with full solutions (calculations, data sets and analyses, and other aspects of solutions) by sending an email to ben.zwickl@rit.edu.

## Table of Contents

* PS1A - Using Python (and a Jupyter notebook) as a calculator
* PS1B - Using constants and special functions, documenting work in a Jupyter notebook
* PS2A - Using lists, plotting data, plotting formulas
* PS2B - Using built-in functions, defining your own functions
* PS3A - Calculations with vector math using components and numpy arrays
* PS3B - Using logical tests, conditional statements (if, elif, else), and loops. Iteratively solving Newton's equations of motion using Euler's method.
* PS4A - Loops and calculating orbits by Euler's method
* PS4B - Importing and analyzing data collected from your smartphone
* PS5A - Numerical derivatives of functions and data
* PS5B - Numerical integration of functions and data
* PS6A - Contour plots applied to visualizing electric potential
* PS6B - Vector plots in 2D and 3D to visualize electric and magentic fields
* PS7A - Numerical calculations of electric fields, flux & Gauss' law (part I)
* PS7B - Numerical calculations of electric fields, flux & Gauss' law (part II)
* PS8A - Random numbers and random Walks
* PS8B - Gaussian/normal random variables, comparing measurements with uncertainty, 2D random walks
* PS9A - Least squares fitting of data to a model
* PS9B - Analyzing audio signals using the Fourier transform and power spectral density
