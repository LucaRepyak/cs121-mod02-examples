Modify the line that reads input using the nextLine() Scanner method to use the next() Scanner method as shown below. What is the result and why?

Result: Instead of printing the whole line you typed it will only print the first word. nextLine() is for the whole line and next() is for a single word.

When prompted for number of miles enter: 12.0 What is the result and why?

Result: Failed to compile. Miles is assigned to an integer but we entered a double.

When prompted for number of miles enter: 12, when prompted for the gallons of fuel used enter: two What is the result and why?

Result: Entering 12 worked fine but when we entered two it once again failed to compile. This happened because gallons of fuel used is assigned to a double variable and we entered a string.

When prompted for number of miles enter: 12, when prompted for the gallons of fuel used enter: 2 What is the result and why?

Result: 6.0 mpg. We enetered in the correct values (double and int) that were assigned to the variables so the program worked with no issues. 