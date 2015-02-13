Notes
=====
Today we learned about lists and for loops.
A list can contain many values. You can have a list of integers ```[3, 4, 6, 8]```, or a list of strings ```["coral", "gold", "azure", "orchid", "PaleGreen"]```. If you want contiguous numbers, you can use ```range(a, b)``` that gives you a list of numbers starting from ```a``` and ends just before ```b```.
You can name these lists, too. For example, you can name the above color list as ```color_book``` by saying ```color_book = ["coral", "gold", "azure", "orchid", "PaleGreen"]```.

When it comes to for loop, the basic syntax is to use a variable to go through all the values in a list. E.g. ```for i in range(3, 9):``` or ```for color in color_book:```. Inside the for loop, you can use the variable ```i``` or ```color``` to draw shapes, change background color, or call functions that do fun stuff.


Extras
======
Here are a few extra things that may help you.

First is a couple of functions that you can use with your turtle pen:
```python
hideturtle() # hide the pen, so it doesn't block anything you just drew
showturtle() # show the pen again
```

Here is something you can use to change the screen size:
```python
screensize(width, height) # so if you want a 800x600 canvas, use scn.screensize(800, 600)
```

Last but not the least is the link for ALL THE COLORS:
https://www.tcl.tk/man/tcl8.4/TkCmd/colors.htm
To use the color, type the string/name on the left as your color name. You may wonder what the numbers on the right mean- they are a way of precisely determine how a color is shown on our screen, which mix three different colors to show all the colors we see on our computers, TVs, phones, etc. If you are still curious, read this: https://en.wikipedia.org/wiki/RGB_color_model


Exercises
=========
* Draw whatever you want with turtle in under 100 lines of code (blank lines, comment lines don't count toward the limit).

Results
=======
You should turn in one program that draws you wonderful creation.
