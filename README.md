# Sudoku_Solver

This project was implemented as my Honours (postgraduate) project which attempted to solely rely on image processing techniques to extract a sudoku grid from a newspaper or article, and to produce its corresponding digital representation. The digital representation can then easily be passed as input to a sudoku solver.
The illustration below shows the input to our solution, along with its corresponding output.
<p align = "center">
  <img src = "https://user-images.githubusercontent.com/26574827/135075237-77d4505d-5b74-46b7-a9f5-6ebe5aed2ca0.jpg" height="330px" />
 </p>


# Data

I created my own dataset by photgraphing images of sudoku puzzles from hard copy books. Thereafter, the data was preprocessed such that 65 images of individual digits of each digit was attained.

# Solution
The implementation heavily relies on python and OpenCV. The solution involves performing a series of image processing techniques such as noise removal (using erosion and dilation operations), extracting contours, performing a perspective transformation, template matching, and many others.
A comprehensive explanation of the solution is presented in the accompanying report in the report, as well as in the python (Jupyter) notebook.
My experiments reveal that the implemented solution achieves a 100% accuracy rate.


