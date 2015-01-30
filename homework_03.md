Notes
=====
Today's class has a lot of details, so let's recap what have learned. Functions can take one or more parameters (sometimes also called arguments). There are a few key points you should remember while using them:
* The parameters need to be _declared_ in the header line of the function, after ```def``` and inside the parentheses. Multiple parameters are separated with comma ```,```.
* Each parameter is given a name when declared, these names are variables, meaning they will remember the values you pass in when you use/call the function. So they can be used to replace _values_. For example, if you declare a parameter ```size```, you can use ```t.forward(size)``` where you previously would call ```t.forward(100)```. The actual length of the line will be determined by the value you pass into ```size```.
* When you use a function that uses parameters, you need to provide the exact same number of values when calling the function; multiple values are separated with comma. The order of parameters also need to match. For example, if you have defined a function whose header line is ```def draw_square(size, color):```, you need to call it with something like ```draw_square(100, "red")```. If you write ```draw_square("red", 100)``` instead, it won't work.
* We talked about a new data type called _Boolean_, a Boolean has two possible values: ```True``` or ```False```. We can use this to control filling the inside of a shape we draw. ```t.fill(True)``` before you draw a shape you want to fill, and when you are done drawing, call ```t.fill(False)``` to stop (and have the last shape filled properly). If Boolean feels a little unnatural to you, don't worry, we'll talk about it more next time with more hands-on examples and exercises.


Exercises
=========
* Write a program that draws 5 squares with the same center, at (0, 0). Draw the largest one first, and decrease the size for each one after. Each square should use a different color. The second and fourth squares should be filled with solid color, while the first, third and fifth ones only draw the outline without filling. You do _not_ need to erase previously filled colors.

Attention: If you see an "IndentationError" when you run your program, make sure you have four spaces at the beginning of each line in your function(s). To verify, move your cursor to the beginning of the line, and press the right arrow key once, if your cursor jumps 4 spaces ahead and land on the first letter, you will need to redo the spaces by press ```delete``` to remove the blank part leading the line, and type spaces four times yourself.  We will discuss this error more in detail next week.

Results
=======
You should turn in *one* program/file.
