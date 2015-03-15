Notes
=====
For those who didn't get a chance to work on the bonus-bonus for last week's homework, it was about making a n-polygon spiral.

Extra
=====
How to figure out the exact size of your screen so you can draw grids that extends from end to end? This function will help you.
```python
scn = turtle.Screen() # first we create a screen
width, height = scn.screensize() # the width and height of the screen will be stored in variable width and height
```
Question: if ```width``` is ```400``` and the ```height``` is ```300```, what are the coordinates of the top-left corner?
Answer: the coordinates would be ```(-200, 150)```

Exercises
=========
* Draw a grid, 10 pixels between neighboring lines on both dimensions, that cover almost the entire screen.

* Bonus 1: draw a grid that is densest on the top-left corner and sparsest on the bottom right corner. A version that I drew looks like this: http://i.imgur.com/2Q0h11W.png

* Bonus 2: draw a grid that is densest near the origin/center, and sparsest near the edges. A vesrion that I drew looks like this: http://i.imgur.com/LTpor3A.png

Your drawings don't have to be exactly the same.

Results
=======
You should turn in one to three programs.
