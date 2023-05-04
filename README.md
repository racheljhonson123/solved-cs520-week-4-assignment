Download Link: https://assignmentchef.com/product/solved-cs520-week-4-assignment
<br>
<p class="ui header product-top-header" title="CS520 Week 4 Assignment Solution">General Rules for Homework Assignments• You are strongly encouraged to add comments throughout the program. Doing so will help your facilitator to understand your programming logic and grade you more accurately.• You must work on your assignments individually. You are not allowed to copy the answers from the others. However, you are encouraged to discuss approaches to the homework assignment with your section mates and the facilitator in your section via the discussion board.• Each assignment has a strict deadline. However, you are still allowed to submit your assignment within 2 days after the deadline with a penalty. 15% of the credit will be deducted unless you made previous arrangements with your facilitator and professor. Assignments submitted 2 days after the deadline will not begraded.• When the term lastName is referenced in an assignment, please replace it withyour last name. You are strongly encouraged to add comments into your program!Create a new Java Project in Eclipse named HW4_lastName. Create a package named cs520.hw4 and complete the following by writing the appropriate classes under this package.

<strong>Part 1 (75 points)</strong>Create a Swing GUI application that displays the following graphics of red and blue cups. The structure is always built from bottom row to top row, left to right in each row.Write a class named Cups1 extending the JFrame class with the following specifications.

a. Declare the integer type instance variables startX, startY, cupWidth, and cupHeight. The first two values represent the top-left coordinates of the first cup block in the bottom row. The next two values are the width and height of each cup.

b. Declate another integer instance variable, baseLength. This representsthe number of cups in the bottom row.

c. Declate another integer instance variable, cupSpacing. This represents the spacing between adjacent cups.

d. In the constructor, specify the appropriate window title using your lastName and assign the above instance variables with the values 100, 300, 25, 40, 7, and 6, respectively.

e. In the paint method, using nested loops, fill the pattern from the bottom row all the way to the top. Notice, that the number of cups decreases by one for each row. Use the baseLength variable to control the loops.

f. In the main method, create the application object, set its size to 550 by 550 and its visibility to true to test the above graphics.

<strong>Part 2 (25 points)</strong>Modify part1 so that the cups look like real cups. Write a newclass Cups2 in the same package for this part.For drawing each cup, use the fillPolygon(int[], int[], int) method fromjava.awt.Graphics. You can reduce the width of the cup on the top by 5 units on the left and 5 units on the right.<a href="https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics.html#fillPolygonint:" target="_blank" rel="nofollow noopener noreferrer">http://docs.oracle.com/javase/8/docs/api/java/awt/Graphics.html#fillPolygonint:</a>A-int:A-int


