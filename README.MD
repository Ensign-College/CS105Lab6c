Lab 6c
======

Submit your finished code to the Dropbox. You will need to pass off the lab with the TA or tutor during their office hours (their information is in the CS 105 Course Information section 
of the Class Resources module), or the instructor in class. Follow the CS 105 Formatting Guide which is also found in the CS 105 Course Information section.

Read the instructions carefully. Make sure your output matches the example run.

Objectives:
===========

In this lab, you will learn how to do the following:

-   Write a **predicate** method
-   Pass arguments to the method
-   Return a boolean value from the method back to your main method
-   Use a predicate method in an if statement

Structure:
==========

Create the following structure in Eclipse for this lab.

**Package Name:** week6\
**Class Name:** Lab6c

Program: isBetween() Method
===========================

In programming, a PREDICATE method is one that returns a boolean value.  For some reason, this tends to confuse new programmers.  There really should be no confusion.  The only 
difference between a predicate method and any other method is that the predicate method returns either *true* or *false* rather than a string or number.

Write a program that asks the user for three whole numbers. Use input validation to ensure the user entered three valid whole numbers.  Have your main() method call a second method that 
you write called isBetween(), passing the three numbers as arguments. Your isBetween() method will determine if the second argument lies between the first and third arguments. If it 
does, return the boolean value ***true*** to main(). Otherwise return the boolean value ***false.***

Your call to the predicate method isBetween() should be in your main() method **and be the condition for an if statement** that prints out whether the second number was between the 
first and the third as shown in the example run.

After the program has finished, ask the user if they would like to play again. Use input validation to ensure the user answered with a 'Y' or 'N'. Keep the program running in an 
infinite loop until the user indicates they want to quit.

Key program requirements:
=========================

-   Do input validation on all three numbers and the 'Y'/'N' play again question
-   isBetween() must return a boolean value
-   The call to isBetween() from within main() should be the condition for an if statement that prints out the result
-   The names of the three variables inside main() which are passed to isBetween() as arguments MUST be different than the names of the three parameters inside of your isBetween() 
method
-   You must complete the Ponder activity below.
-   Submit the following .java file:
    -   Lab6c.java

Ponder:
=======

Discuss the following with your partner. **Failure to do this activity and discuss these questions before you attempt to pass off your program will result in a failed pass off**.

The instructor has required the variables inside main() which are passed to isBetween() as arguments MUST be different than the names of the three parameters inside of your isBetween() 
method.

-   Discuss whether this is a Java requirement or simply a requirement of your instructor.
-   Discuss why you think the requirement was made.

Example Run:
============

*This program will ask the user for 3 numbers and determine if the second number lies between the first and the third.*

*Please enter the low number: 50*\
*Please enter the number to be tested (the between number): 16*\
*Please enter the high number: 189*

*16 DOES NOT lie between the numbers 50 and 189.*

*Would you like to play again? (Y/N): y*\
*Please enter the low number: 40*\
*Please enter the number to be tested (the between number): 42*\
*Please enter the high number: 45*

*42 lies between the numbers 40 and 45.*

*Would you like to play again? (Y/N): n*
