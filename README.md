# Capstone-Shell-Scripting

## Bash Script For Generating a Multiplication table

### Objective

This project will create a Bash Script that generates a multiplication table for a number entered by the user. 
It will incorporate the practice of loops, handling user inputs with ‘read’ commands, and applying conditional logic in Bash Scripting.

### Script Summary

* The Script will prompt the user to enter a number for the multiplication table.
* Ask if they want a full table or a partial table.
if partial, prompt for the start and end numbers of the range.
* Validate the range of inputs and handle invalid or out-of-bound entries.
* Generate and display the multiplication table according to the specified range.
* Provide clear output formatting.
* Apply enhanced user interaction etc.

We use the vim text editor to develop our script then run it on Ubuntu terminal as shown below.

![alt text](<Images/script 1.PNG>)

![alt text](<Images/script 2.PNG>)

![alt text](<Images/script 3.PNG>)

![alt text](<Images/script 4.PNG>)

![alt text](<Images/script 5.PNG>)


The script output generates a multiplication for a full table as entered by the user with an added feature of generating a full table using List form loop as well as c-style loop.

![alt text](<Images/script 6.PNG>)

We then run the script where the user chooses a partial table as shown below.

![alt text](<Images/script 7.PNG>)

Where the user inputs an invalid range, the script defaults to a full multiplication table between 1 and 10.

![alt text](<Images/script 8.PNG>)
![alt text](<Images/script 9.PNG>)

**Note:**

The script uses comments to explain the different parts of the script including which parts uses List form loop and which parts use C-style loop.
There is a clear format for the script to enhance reading.
The script applies several new use cases such as;
( “==’’) - used for string comparison.
( “&&” ) – used as the logical AND; both are used in adding proper validation for the input range. 
