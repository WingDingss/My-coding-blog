---
title: "Random Shapes"
date: 2024-05-12
---
Yet another addition into the collection of random code samples, this one instead being about the randomness of shapes, their size, and their positioning, instead of the previous walkers which was a singular
string being randomly moved. The random shapes instead focuses on pure chaos, and my final sample has proven that too much chaos, can cause the PC to suffer

![The chaos of shapes](/My-coding-blog/images/randomshapes.png)

We can see here with the code snippet, that when it comes to a variable in the code, everything has been inputted as random.
```
function drawTile(across, down, step)
{
 fill(random(0,255),random(0,255),random(0,255))
  push()
  translate((across+1)*step, (down+1)*step)
  //angleMode(DEGREES)
  //rotate(frameCount*across+down*2222)
  //rectMode(CENTER)
  //let r=random()
  ellipse(random(step),random(step),random(step), random(step))
  pop()
  
  push()
  translate((across+1)*step, (down+1)*step)
  //angleMode(DEGREES)
  //rotate(frameCount*across+down*2222)
  //rectMode(CENTER)
  //let r=random()
  ellipse(random(step),random(step),random(step), random(step))
```
And when all variables are inputted as random, it will always give unique results when testing around, this is what drives my exploration into the current unkown, replacing current variables to see how much
of a drastic difference it would make to the overall piece on the canvas.

![The chaos of shapes](/My-coding-blog/images/randomshapes2.png)

Above shown we can see a variation of the code, this time instead of only ellipses, there is now one of every shape present within the random shapes, making a much more expansive in their positioning around the canvas.
Further testing could reveal much more unique and different approaches by mixing, matching, adding and subtracting different shapes to the overall code block. Not only that, but direction could also be implemented next
time, giving each shape a longer lifespan to avoid the lag made, along with adding rotation to each shape, providing even more randomness and anarchy.

