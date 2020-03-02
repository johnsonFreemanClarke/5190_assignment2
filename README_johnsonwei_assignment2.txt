README
CS 5190 Assignment 2 
Johnson Wei (004150718)

Image files and their description:
cppEnvDesign - original image file used for the project
cv2CannyResult - cv2.Canny function output image
cv2LaplacianResult - cv2.Laplacian function output image
myCannyEdgeResult - my implementation of (canny edge) output image 

The original image file will be provided within johnsonwei_assignment2.zip
so that the user can set their own path relative path (optional).
Changes need to be made so that the cv2.imread function contains
the relative path as a string. 

Anytime the cv2.imwrite function is encountered, please set relative
path accordingly to your respective directory path.

ex: img = cv2.imread('/change/this/to/your/path', 0)
OR
saved_img = cv2.imwrite('/change/this/to/your/path', name_of_img)

Source code developed on Jupiter notebook.
The jupyter notebook is labeled in a step-wise manner and commented
for clarity. This code can also be viewed on github with the link:

https://github.com/johnsonFreemanClarke/5190_assignment2

Notes: The bonus feature of a deep search (recursive function) has been
implemented for the Hysteresis function (step 4). Recursive function is 
called checkWeakNeighbors(weak, updated, row, col)