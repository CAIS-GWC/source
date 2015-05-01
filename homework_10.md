Notes
=====
Today we introduced another way of using loop- the while-loop.

While loop is a little bit like the ```if``` statement, in the sense that the content of the loop will be executed only when the condition in the ```while``` is true. Unlike the ```if``` statement which only executes the content once, ```while``` loop will keep executing the content repeatedly, until the condition is no longer true. Also, it is important to assign a value to the variable we are using in the loop, this is called "initialization".
For example,
```python
n = 1
while n < 128:
    print n
    n = n * 2
```
The result of the above code should be
```
1
2
4
8
16
32
64
```
Question: what would be the result if we swap the two lines inside the loop?
Another question: what would happen if we forget to add the line ```n = n * 2```?

Extra
=====
Because while loop requres the initialization of variables, such as your turtle's coordinates, it would be useful to know where you turtle is easily. Here's the command that gives you that.
```python
# If your turtle pen is named 't'
# The following line stores turtle's current coordinates in variable x and y
(x, y) = t.pos()
```

Exercises
=========
* Draw a 'shaft', and start the turtle from the end of the shaft on one wall, animate turtle to move at a 45 degree angle until it 'hits' the other wall.

* Bonus 1: turn the turtle by 90 degrees, and move the turtle until it hits the first wall.

* Bonus 2: keep bouncing the turtle between walls until the turtle is out of the shaft.

Results
=======
You should turn in one to three programs.
