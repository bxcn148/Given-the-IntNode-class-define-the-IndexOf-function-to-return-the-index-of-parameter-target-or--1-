Download link :https://programming.engineering/product/given-the-intnode-class-define-the-indexof-function-to-return-the-index-of-parameter-target-or-1-if-not-found/


# Given-the-IntNode-class-define-the-IndexOf-function-to-return-the-index-of-parameter-target-or--1-
Given the IntNode class, define the IndexOf() function to return the index of parameter target or -1 
Note: The first index after the head node is 0.

Ex: If the list contains:

head -> 14 -> 191 -> 22 -> 99

IndexOf(headNode, 22) returns 2.

Ex: If the list contains:

head ->

IndexOf(headNode, 22) returns -1.

A linked list is built in this lab. Make sure to keep track of the head node.

(1) Define the class ContactNode per the following specifications:

Private data members

string contactName

string contactPhoneNumber

ContactNode* nextNodePtr

Constructor with parameters for name followed by phone number (1 pt)

Public member functions

GetName() – Accessor (1 pt)

GetPhoneNumber() – Accessor (1 pt)

InsertAfter() (2 pts)

GetNext() – Accessor (1 pt)

PrintContactNode()

Ex: If the name is Roxanne Hughes and the phone number is 443-555-2864, PrintContactNode() outputs:

Name: Roxanne Hughes

Phone number: 443-555-2864

(2) Define main() to read the name and phone number for three contacts and output each contact. Create three ContactNodes and use the nodes to build a linked list. (2 pts)

Ex: If the input is:

Roxanne Hughes

443-555-2864

Juan Alberto Jr.

410-555-9385

Rachel Phillips

310-555-6610

the output is:

Person 1: Roxanne Hughes, 443-555-2864

Person 2: Juan Alberto Jr., 410-555-9385

Person 3: Rachel Phillips, 310-555-6610

(3) Output the linked list using a loop to output contacts one at a time. (2 pts)

Ex:

CONTACT LIST

Name: Roxanne Hughes

Phone number: 443-555-2864

Name: Juan Alberto Jr.

Phone number: 410-555-9385

Name: Rachel Phillips

Phone number: 310-555-6610

A pedometer treats walking 2,000 steps as walking 1 mile. Write a StepsToMiles() function that takes the number of steps as an integer parameter and returns the miles walked as a double. The StepsToMiles() function throws a runtime_error object with the message “Exception: Negative step count entered.” when the number of steps is negative. Complete the main() function that reads the number of steps from a user, calls the StepsToMiles() function, and outputs the returned value from the StepsToMiles() function. Use a try-catch block to catch any runtime_error object thrown by the StepsToMiles() function and output the exception message.

Output each floating-point value with two digits after the decimal point, which can be achieved by executing

cout << fixed << setprecision(2); once before all other cout statements.

Ex: If the input of the program is:

5345

the output of the program is:

2.67

Ex: If the input of the program is:

-3850

the output of the program is:

Exception: Negative step count entered.
