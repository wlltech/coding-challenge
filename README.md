# coding-challenge

Simple console version of a painting JAVA program

Coding challenge Introduction to the problem

Please, implement the solution using JAVA, any JAVA framework is fine. As a minimum, please use the provided test data to indicate that the solution works correctly.

Canvas Paint tool

You're given the task of writing a simple console version of a painting program. At this time, the functionality of the program is quite limited but this might change in the future. In a nutshell, the program should work as follows:

1. Create a new canvas
2. Start painting on the canvas by issuing various commands
3. Quit
4. 
At the moment, the program should support the following commands:

C w h
L x1 y1 x2 y2
R x1 y1 x2 y2
Q

Sample I/O

Should create a new canvas of width w and height h.

Should create a new line from (x1,y1) to (x2,y2). Currently only horizontal or vertical lines are supported. Horizontal and vertical lines will be painted using the 'x' character.

Should create a new rectangle, whose upper left corner is (x1,y1) and lower right corner is (x2,y2). Horizontal and vertical lines will be painted using the 'x' character.

Should quit the program.

Below is a sample run of the program. User input is prefixed with ’enter command:’.

enter command: C 20 4 
---------------------- 
|                    | 
|                    |  
|                    |  
|                    | 
----------------------

enter command: L 1 2 6 2  
---------------------- 
|                    | 
|xxxxxx              | 
|                    | 
|                    | 
---------------------- 

enter command: R 16 1 20 3 
----------------------
|              xxxxxx|
|xxxxxx        x    x|
|     x        xxxxxx|
|     x              |
----------------------

enter command: Q
