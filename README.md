Batman-Logo-Drawing-with-Python-Turtle

Explanation:

First Part:
a. In the first part of Draw Batman Logo with Python Turtle, we will import the turtle and the math module.
   Then, we will set “pen” as the turtle pen and speed as 500.
   Now, set the screen of the turtle to “window” and
   set the background color of the screen to black and the pen color to yellow.

b. Likewise, set the value of the “avinash” variable as 20.


Second Part:
a. Move the turtle left at an angle of 90 degrees and pick the pen up. Then, goto(-1*avinash,0) and put the pen down.

b. We will now be using the math module.
   Similarly, create a for loop with the range of { -7*avinash,-3*avinash,1 }. Inside this loop,
   set the value of the “x” variable as (a / avinash). Then, set the value of “rel” to math.fabs(x).
   This will return the float absolute of the “x”.
   Likewise, we will set the value of y as { (-math.fabs(rel-1))*math.fabs(3-rel)/((rel-1)*(3-rel)))*(1+math.fabs(rel-3)/(rel-3))*math.sqrt(1-(x/7)**2)+(4.5+0.75*(math.fabs(x-   0.5)+math.fabs(x+0.5))-2.75*(math.fabs(x-0.75)+math.fabs(x+0.75)))*(1+math.fabs(1-rel)/(1-rel) } in side of a sqrool of the power 1.5; 
   which will determine the angles of the turtle. Similarly, take the “pen” to (a, y*avinash)

c. Coming out of the loop, make the pen go to (-1*avinash, 3*avinash). Do the same as in the code below.
   pen.goto(-1*avinash,3*avinash)
   pen.goto(int(-0.5*avinash),int(2.2*avinash))
   pen.goto(int(0.5*avinash),int(2.2*avinash))
   pen.goto(1*avinash,3*avinash)


Third Part:
a. In this part of the code, create a for loop with the range of { 1*avinash+1,3*avinash+1,1 }. 
   Inside this loop, set the value of “x” variable as (a/avinash) and set rel as in the second part. 
   All the other for loops are of the same type but with different ranges and arguments.

b. At last, pick the pen up and goto(300, 300) and end the code with exitonclick() method.
