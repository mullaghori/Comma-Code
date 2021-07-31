>From the book: Automate the Boring Stuff With Python. Writer: AL Sweigart

# PICTURE-GRID
It is a practice project for python beginners.

Say, you have a list of lists, where each value in the inner list is a one-character string, like this:
```
Grid = [['.', '.', '.', '.', '.', '.'],
        ['.', 'o', 'o', '.', '.', '.'],
        ['o', 'o', 'o', 'o', '.', '.'],
        ['o', 'o', 'o', 'o', 'o', '.'],
        ['.', 'o', 'o', 'o', 'o', 'o'],
        ['o', 'o', 'o', 'o', 'o', '.'],
        ['o', 'o', 'o', 'o', '.', '.'],
        ['.', 'o', 'o', '.', '.', '.'],
        ['.', '.', '.', '.', '.', '.']]
```

You can think of a grid[x][y] at being the character as x-coordinate and y-coordinate of a "picture" drawn with text characters. The (0,0) origin will be the upper-left corner, the x-coordinate increases going right, and the y-coordinates increases going down.
Copy the provious grid value, and

***👉 No.1 Write code that uses it to print the image;***
```
..oo.oo..
.ooooooo.
.ooooooo.
..ooooo..
...ooo...
....o....
```

*HINT: You will need to use a loop in a loop in order to print grid[0][0], then grid[1][0], then grid[2][0], and so on upto grid[8][0]. This will finish the first row, so then print a new line. Then your program should print grid[0][1], then grid[1][1], then grid[2][1], and so on. The last thing your program will print is grid[8][5].
Also, remember to pass the end keyword argument to print() if you don't want to print a newline printed automatically after each print() call.*
