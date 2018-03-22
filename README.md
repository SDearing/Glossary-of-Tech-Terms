# Glossary-of-Tech-Terms
## Programming Terms ##
* Algorithm: A set of rules/instructions that are used to solve a certain problem, in most cases the algorithm is run by a computer to create a program that will solve a problem.
* Object Oriented Paradigm: A type of coding paradigm, which focuses on the creation of objects within the program that work together to create a solution. This process involves creating classes which acts as a template, an iterance of the class would be called an object. A object has 2 characteristics attributes and methods. Attributes are the features of the object, for example if the object was a cat a attribute could be breed. A method is what the object can do, for example if the object was a dog a method could be fetch.
* Procedural Paradigm: A type of coding paradigm, which focuses on calling upon functions to create a solution. These functions are created by the programmer to solve different parts of the problem.
* Event Driven Paradigm: A type of coding paradigm, in which the flow of the program is decided by events such as user actions.
## The Relationship Between Coding Paradigms (Object Oriented, Procedural, Event Driven)
The procedural paradigm focuses on the creation of procedures and calling upon those procedures to complete a program, the event driven paradigm also involves the creation of procedures however these functions are only called when a certain event has occured i.e. a press of a button. With the object oriented paradigm instead of creating functions, it creates classes to create objects. The classes are used to create instances(objects) to solve solutions instead of relying on an event like the event driven paradigm.  
## The Process of Building an Application
#### Step 1: Build a Development Team (or work alone)
The first step is to make a development team, the people you choose should have some experience in coding as it will increase the effeciency of the actual development stage. Alternatively you can choose to work alone, however the workload will be alot higher.
#### Step 2: Development Plan
Before you can start development, it is vital that you fully understand what the solution (app) will need to do and what functions it will need to serve, this is important, especially in a team setting, as it will make sure that you have a clear direction in the development stage. Once the idea for the app has been established you will need to identify every function the app will serve and plan out how the app will work, this is usually done by designing the algorithm for the app, either through a flowchart or by the use pseudocode, this helps break the problem down so the team can fully understand part of the app that they will need to develop.
#### Step 3: Project Management Plan
After the idea has been fully established, you will then need to plan and document the cost, scope, time, quality, communication, risk and resources needed. The cost of the project describes the budget of your project and what those expenses will be. The scope of the project is the extent of the functions you will be including in your solution and more specifically what functions you will be leaving out. The time of the project describes how much time you plan to spend on the project with milestones dates to aim for during development. The quality section is where you plan out the actions you will be taking to assure quality in your application. Communication is the section of the document where you plan out how you will keep in contact with your team and track eachothers progress on tasks, this section also describes any stakeholders for the app and how they will informed on the progress of development. The next section is risk which is where you would plan out possible risks that could disrupt the development process, the likelihood of the risk and methods needed to reduce the risk. Finally the resource section of the document is where you would list the resources you would need to complete the project, this would involve any software or hardware you need.
#### Step 4: Development
This is the stage where the actual programming of the algorithm can begin. There are multiple methodologies that a developer can use to structure the development process, however most development processes involve creating a prototype and developing upon the prototype, creating multiple versions untill a version is created that meets all the standards set in the development plan. The development process is usually completed using an IDE and a high level programming language. IDE stands for integrated development environment and aids the programmer when writing code and a high level programming language is the language that is used to program the application, an example of this is C++.
#### Step 5: Testing
The testing phase of the project can either be conducted after development or during the development process, testing code as it is developed. The testing stage is very important as it identifies and removes bugs that could drastically alter how the app works, and makes sure that the app works exactly as intended. Before testing begins, you should plan out the tests you are going to conducts, the tests should be thorough and test every function of the app, and the desired outcome of each test should be taken into account.
#### Step 6: Release and Maintanence
Once testing is fully complete and you are sure it works correctly the app can be released to either the client or the public, once released you should make sure you are taking feedback from stakeholders and using the feedback for planning future iterations of the app to fix any issues or bugs, and/or to add new features.
## The Debugging Process
Debugging, in software development, is a process that involves finding and fixing errors and bugs in your software. Debugging a very important tool used by developers when trying to fix bugs in their code, from when they write the first lines of code, to when they are testing the final prototype.
The Process:
#### Step 1: Find and Describe the Bug
Before the debugging process can begin you must fully describe what the issues are being caused by the bug.
#### Step 2: Recreate and Snapshot the Bug
Next you must try and reproduce the bug, creating a  of the state of the code when the bug appears (variable values, etc.)and what function is being run.
#### Step 4: Analyze the Snapshot
Begin to look at the functions being run around the time when the bug occurs and look for the individual function(s) that could be causing the bug. Once you have found the section of code that is causing the bug you can begin to think of possible solutions to fix the bug.
#### Step 5: Test the Solution(s)
Once you have implemented your solution into the code, you need to test it. If the solution fixes the bug and creates no new bugs then the solution was successful. If the solution does not work or creates new errors, you will need to repeat these steps. A possible issue could be you created a snapshot at the wrong point of the code runtime.
## The Debugging Facilities Available in the IDE
The debugging process can be less time consuming when using an IDE, this is because it provides a debugger with many different facilities to aid in discovering and fixing errors, such as
#### Finding Runtime Errors
Runtime errors are errors that can only occur while the code is running, an example of this being a function that is expecting a string but recieves an integer. The debugger in an IDE can identify where this error is located and higlight it so the programmer can find it and fix it.
#### Pausing and Editing Code During Runtime
Some debuggers can allow you to pause your code while it is running this can allow you to edit the code, allowing you to see realtime results of the changes you make. This allows you to find solutions to bugs in your code quicker as you can more effeciently test different solutions.
#### Changing Variable Values During Runtime
Additionally some debuggers allow you to change the values of variables within you code while it is running. This is helpful for developers that want to test their software at certain stages or test how their code runs under variable changes while the code is running. 
## The Steps from Writing Code to Execution
Once you have written your code their are certain steps the computer needs to complete before the code can be executed.
#### Step 1: Using an Interpreter/Compiler
A processor cannot understand the code you have written as the langauge you wrote it in is a high-level language, a processor can only understand machine code. So first, the computer must translate the high-level code to machine code, to do this the computer uses an interpreter or a compiler. An interpreter translates one line of code and then executes it one at a time, whereas a compiler translates the whole source code before executing it.
#### Step 2: Obtain Memory
All processes in a computer require memory, so before any lines are executed the operating system of the computer must allocate a certain amount of memory for the process of running your code before it can be ran by the processor. Once the memory has been allocated the computer can then run the code.
#### Step 3: Run Code
The processor runs the stored machine code, and therefore runs your written high-level code.
## How Technical Solutions Can be Compared
The following factors are judged when comparing technical solutions:
* Robustness: Robustness refers to how resilient a peice of code is, meaning that the code has minimal bugs and crashes extremely rarely. Robustness also refers to a softwares ability to withstand erroneous input, which means inputs that have the ability to cause issues to the software, i.e. a user inputting a integer when the software is expecting a string.
* Efficiency: Efficiency refers to the speed of the runtime of the execution of software, meaning how long the software takes to give the desired solution. Speed of runtime also refers to how long the actual source code is, i.e software with a minimal amount of lines of source code are more effecient that software with large of amounts of lines of source code.
* Fitness: This refers to whether or not the solution fufils its intended purpose, or if it is being used for a different purpose.
* Cost of Software: This refers to how much the consumer would have to pay for the software, being a annual cost or a one time cost. Software needs to be priced fairly for it to gain popularity in its respective market.
## The Importance of Team Dynamics 
Team dynamics are the aspects that affect the relationship between members of a team and how it affects how the team functions together. Good team dynamics start with an effective project manager, a good manager needs to define the nature of the group through positive guidance and effective management of tasks. Effective communication is a important team dynamic, the project leader must give directions and tasks clearly, to make sure that every member fully understands the task they are given. The members of the team need to feel comfortable so that they can relay problems and questions to each other and the manager. Motivation is also a key aspect of team dynamics, as motivated members are eager to contribute towards the project, whereas unmotivated members may only produce just enough work to avoid scrutiny jeprodising the success of the project. To ensure motivation within your team use incetives to encourage work, for example give rewards to members of the team that achieve their tasks ahead of the deadline. Finally effeciency is a very important team dynamic as it allows each member to work to their fullest.
## How to Address Software Requirements in Projects 
