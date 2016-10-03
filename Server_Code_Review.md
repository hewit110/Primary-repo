Gitub URL of the project being reviewed: https://github.com/hewit110/PrimaryRepo
Name of Reviewer: Hein Thu
Name of Programmer: Kevin Hewitt
Date of Review: 10/02/2016

On a scale of 1 to 5, I give this code a rating of 2 based on the following criteria:

1  The program has syntax errors and does not compile
2  The program compiles successfully but generates runtime errors
3  The program compiles and runs but does not perform correctly and does not produce correct results
4  The program compiles and produces correct output but does not follow assignment/class guidelines or is insufficiently documented
5  The program produces correct output and is well written and well documented

Suggestions for improving the code:

- The program crashes at line 129  because the "IPAddress" is null for the first run so the comparison causes nullPointerException. Also use .equals() since it is an object
- For line 89 and 131, the server should send the message to the clients instead of printing it out. (The clients do not know what is going wrong)
- For line 66, the lines are supposed to be "HELLO Red" and "HELLO Blue" according to the instruction. (You need to stick strictly to the protocol to work without errors)
- For case 2, you should also check if the client is sending "HELLO Red" or "HELLO Blue"
