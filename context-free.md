[shape_rules]: https://github.com/MtnViewJohn/context-free/wiki/Shape-Rules

# Context Free

##  Who is this programming language for?
This programming language is for digital artists.


## What is easy to do in this language? Why is it easy?
I thought it was pretty easy to make simple shapes like circles and triangles, and move
them around and simple scaling operations. Those are very easy to use the default shapes
for and are intuitive to watch how changing the parameters affect the whole image. The system
for creating custom shapes, and having a startshape also felt intuitive to me, like calling
functions.

## What is hard to do in this language? Why is it hard?
I found it really hard to do more complicated things like creating a line that curved, and stretching a shape, like making a circle and oval, and also changing the color. None of it felt intuitive. I had to fight what I thought the grid and scale was and what it actually was. With the
exception of changing the color, the language also has no guaranteed order of when the shapes get
built, so every time I added a new shape to a layer it often affected the other shapes([Shape Rules][shape_rules]). That made it hard to say "oh I want to add this other thing" (like I wanted to give my fish a mouth) because for some reason, adding that shape would cause the eye shape to move behind the body and no longer be visible.


## How did you learn how to program in this language?
I used a combination of reading the documentation and using the example code provided with the
program as models.


## What is the underlying _computational model_ for this programming language? 
It takes the startshape and then takes the different shapes and their grammar rules to find the least complex versions of those shapes and then it draws those shapes to create the more complex ones that make up the startshape.


## What do you think is interesting about the ContextFree program you wrote?
I thought the way I made the tail was interesting. Essentially I used overlapping triangles that were rotated different angles and had different saturations to not only make the color interesting
but also give it a bit of movement. If I were to make it more complicated, I would make more triangles and use a gradient of saturation to make the tail look even more three dimensional.

