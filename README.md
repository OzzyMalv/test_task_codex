# Another test task

Terms:
1. The problem must be solved in JavaScript.
2. Your JavaScript code must comply with the latest ES2018 specification
3. The use of React or Vue is strongly encouraged!
4. The drawing field must be made in the form of an HTML page (place HTML
elements as per your application logic), don't use the `<canvas>` element and
its API
5. Make sure the program finished and covered in tests!

The task is to write a simple drawing program that executes the sequence
commands from the file Input.txt and outputting output.txt. Use the following commands:

**Canvas:** create a canvas with width w and height h.

**Line:** draw a line from (x1, y1) to (x2, y2), using pseudo graphic to draw
the character "x". Only horizontal and vertical lines supported.

**Rectangle:** create a rectangle with top-left corner at point (x1, y1), bottom-right
angle at the point (x2, y2). Vertical and horizontal lines must be drawn
pseudo-graphic characters “x”.

**Bucket Fill:** fill the entire area (x, y) with color ("color", c), similar to how it works
fill tool in graphics editors.

**Important: you can draw only if the canvas created!**

### Input file (txt)
```
C 20 4
L 1 2 6 2
L 6 3 6 4
R 16 1 20 3
B 10 3 o
```

### Output file (txt)
```
----------------------
|                    |
|                    |
|                    |
|                    |
----------------------
----------------------
|                    |
|xxxxxx              |
|                    |
|                    |
----------------------
----------------------
|                    |
|xxxxxx              |
|     x              |
|     x              |
----------------------
----------------------
|               xxxxx|
|xxxxxx         x   x|
|     x         xxxxx|
|     x              |
----------------------
----------------------
|oooooooooooooooxxxxx|
|xxxxxxooooooooox   x|
|     xoooooooooxxxxx|
|     xoooooooooooooo|
----------------------
```


##### Something similar to paint... ~~Boring as f...~~