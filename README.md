# CS5004CommandPatternTeam2

30 pts
Full Marks
The GitHub README includes clear information on the pattern. We understand when is a good idea to use it. There is an example.

30 pts
Full Marks
The GitHub README describes the code and explains how to run it. There is a UML diagram for the code.

I. Introduction

The Command Pattern is a behavioral design pattern that encapsulates a request as an object , allowing you to parameterize clients with different requests , queue or log requests, and support undoable operations. In this pattern, you create a Command object that has all the necessary information, such as the receiver object, the method to call, and the parameters to pass. The client code then creates an instance of the Command object and executes it when needed. The key benefits of the Command Pattern are that it decouples the client code from the receiver object and allows you to add new commands without modifying the existing code. It also allows you to implement undo/redo functionality by storing a history of executed commands. Overall, the Command Pattern is used when you want to encapsulate a request as an object and pass it around as a first-class citizen. This pattern is widely used in GUI toolkits, where you can create various commands for button clicks, menu selections, and keystrokes, and map them to various methods of different objects.


II. Implementing the Command Pattern

The steps for implementing the Command Pattern design pattern are:
    1.Declare a Command interface with an execute method to define the required signature for all commands.
    2.Implement the Command interface with concrete classes that encapsulate specific behavior and data.
    3.Declare an Invoker class that receives and executes commands. The Invoker can maintain a command history or queue for undo/redo functionality.
    4.Declare a Receiver class that performs the actual work of the command. The Receiver is the object that the command will act upon.
    5.Declare a Client class that creates the concrete commands, sets their receivers, and passes them to the Invoker to execute.
    6.Test the implementation to ensure that it works correctly.

III. Case Study: Implementing the Command Pattern in a Project

IV. Conclusion

V. References

“Command pattern,” Wikipedia, 17-Feb-2023. [Online]. Available: https://en.wikipedia.org/wiki/Command_pattern. [Accessed: 21-Mar-2023]. 

W. by: baeldung, “The command pattern in Java,” Baeldung, 19-Sep-2022. [Online]. Available: https://www.baeldung.com/java-command-pattern. [Accessed: 21-Mar-2023]. 

“C# command,” Dofactory. [Online]. Available: https://www.dofactory.com/net/command-design-pattern. [Accessed: 21-Mar-2023]. 
“Design patterns - command pattern,” Tutorials Point. [Online]. Available: https://www.tutorialspoint.com/design_pattern/command_pattern.htm. [Accessed: 21-Mar-2023]. 
“Command pattern,” GeeksforGeeks, 13-Jun-2022. [Online]. Available: https://www.geeksforgeeks.org/command-pattern/. [Accessed: 21-Mar-2023]. 
“Command,” Refactoring.Guru. [Online]. Available: https://refactoring.guru/design-patterns/command. [Accessed: 21-Mar-2023]. 





