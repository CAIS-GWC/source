Notes
=====
We learned more about Boolean type this week. whose possible value can be either True or False. We've also looked at a bunch of _expressions_ that are about comparisons: e.g. ```1 == 1```, ```2 > 3```, ```4 - 2 >= 2```, ```color == "red"```, etc. These expressions, like all expressions, eventually can be deduced to some value, and that value is a boolean. An expression that can be evaluated to a boolean is used a lot in helping us decide whether certain actions should be taken or not. For example, we can say we want to change the background color to ```green``` only if the color of turtle is ```red```. And we do this with an ```if``` statement that looks like this:
```python
if color == "red":
    scn.bgcolor("green")
```

Exercises
=========
* Finish the exercise from last week if you haven't done so, but this time, using ```if``` statements in your drawing function, to change the background color according to the color parameter. You can pair any colors together according to you personal taste. At the end, set the background color back to ```white``` after drawing all the squares.

* Bonus: draw 5 or more squares at different locations on the screen. Using ```if``` statements to decide whether you want to fill each square or not: if the size is greater than 75, don't fill it; only fill squares whose size are less than or equal to 75.

Results
=======
You should turn in one or two program/file.
