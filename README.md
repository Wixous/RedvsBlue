# RedvsBlue
Author: Ian Rodden
Date Last edited: 8/31/2017
Class this is for: CS 4500, Fall 2017
Language coded in: JavaScript
Title: A pretty strange game
Version 2.0

TO RUN THIS CODE: Copy and paste it in its entirety into w3schools' JavaScript environment found at: https://www.w3schools.com/js/tryit.asp?filename=tryjs_myfirst
You will need to first delete the code found in the left hand pane. Then you will paste this entire document into the left hand pane. Then you will click the run button 
that is right above this left hand pane. Following that you can click the button that now appears in the right hand pane to run this programs simulation.

These are the specifications for Version 1.0 as given by the customer(my teacher):

Imagine there is a 10 by 10 grid sketched out on a metal wall. You place a red magnetic marker in the lower left hand cell of the grid. Now you repeat the following:

1. Randomly choose a direction: up, down, left, or right. Each direction should be equally likely, over the long haul, to be chosen.  Call the direction D.

2. Randomly choose a number of steps, either 0, 1, or 2. Each of these should be equally likely over the long haul.  Call the number of steps N.

3. Try to move the red marker N steps in the D direction. If that move would take you off the grid, go back to step 1 without moving the marker. 

4. If that move leaves you on the grid, move to the new position. If the new position happens to be the upper right hand corner of the grid, 
   then you are done with the game (you win!).

5. It is at least theoretically possible that this game could go on for a very long time. 
If you have done step one 1,000,000 times, stop the game before doing step one 1,000,001, and report that situation.  

You are to simulate this (pretty strange) game. The program that you use must run on the PC at the front of our classroom. 
You may use any programming language that you’d like, as long as you can deliver one of three things:

1. A URL where your program runs. (In other words, your simulation is web-based.)

2. A single executable file that I can download and run on the computer at the front of our classroom without any modifications on my part.

3.  A JavaScript program that I can copy and paste into the W3 JavaScript Tutorial system and execute that way.

Notice that I do not intend to compile anything. You deliver a URL , an executable file, or a JavaScript source file; and I execute. 

When your simulation finishes, it should print to the screen this information, appropriately labeled:

1. How many times was step 1 executed? Did the game finish because the marker got to the upper right, or because you ran out of steps?

2.  Keep track of how many times either of the markers landed in a particular cell (we’ll call that a “touch”).  
A touch includes the starting cell, and wherever a move finishes. What was the maximum number of touches for any cell? What was the minimum number of times a cell was touched? 
What is the average number of touches to a grid cell? The minimum and maximum should be non-negative integers; the average should be a positive real. 
(Note: the minimum and maximum may occur on multiple cells in the grid; that’s fine.)

Version 2.0 specifications as given but by the customer(my teacher):
All Requirements of Version 1.0
Version 2.0 requires you to revise and extend your version 1.0 program. You will use graphics to show the user what is happening as the random walk touches various cells. 
This must be done using Javascript in a single file. 
Your program also must request from the interactive user the number of columns and the number of rows in the grid. 
These two numbers must be integers, and between 5 and 20 inclusive. Be wise about making sure you get the proper input from the user. 
The marker will again start in the lower left corner of the rectangular grid of the specified size.  
