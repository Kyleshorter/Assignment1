# Assignment1
Data Structs
CS 3358 Assignment 1 
Due: 11:55pm Thursday, September 19, 2019 
Instructor: Kecheng Yang (yangk@txstate.edu) Instructional Assistant: Cody Blakeney (cjb92@txstate.edu) 
 
This assignment have two parts, under the folder stack and queue, respectively. Parts of codes are given in the .cpp and .h files. 

The places you need to fill out in the codes are marked by // TODO. 
 
Both the implementations for the stack and queue are supposed to be array-based in this assignment. 
 
1. (40’) In myStack.cpp, implement the member functions of the class myStack, which is the class for integer stacks. 
 
2. (20’) In stackTest.cpp, complete the implementation of function postfixTest(), which use an integer stack to evaluate
post-fix expressions. For simplicity, you can assume the post-fix expression is input character by character 
(i.e., not an entire string), and each operand is a non-negative, single-digit integer (i.e., 0,1,…,9). 
However, you are supposed to detect invalid/ illegal post-fix expression input, e.g., “4 5 + -“. 
 
3. (40’) In myQueue.h, implement the queue class template, myQueue.  Keep in mind, the arrayLength needs to be one more than the 
capacity of the queue. Also, under this implementation, make sure your calculation of currentSize is correct, and the conditions 
for “Full” and “Empty” are correct. One shortcut could be: once you make sure currentSize() is implemented correctly, you might 
use it in isFull() and isEmpty(), and the number of elements in the queue must range from 0 to arrayLength – 1. 
 
Compiling:  For the stack part, you will need to compile myStack.cpp and stackTest.cpp separately to two .o files and then link the 
together to the executable. For the queue part, you can directly compile queueTest.cpp to the executable. Two PDF guides in TRACS 
might be helpful, if you are not familiar with these in the Linux environment using the g++ compiler. 
 
Submission: You should submit your work via the assignment tag in the TRACS system. You should put myStack.cpp, myStack.h, 
stackTest.cpp into the folder /stack, put myQueue.h, queueTest.cpp into the folder /queue, and pack the folders /stack  and 
/queue into a single .zip file to upload to TRACS. The .zip file should be named as a1_yourNetID.zip, such as a1_zz567.zip 
 
Sample tests: Note that successes in getting the following test results do not guarantee the correctness of your work and 
therefore do not guarantee you a satisfactory grade, whereas failures in getting the 
following test results probably do indicate flaws in your work and you may lose points.
