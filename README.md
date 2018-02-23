# Glossary-of-Tech-Terms
## Programming Terms ##
* Algorithm: A set of rules/instructions that are used to solve a certain problem, in most cases the algorithm is run by a computer to create a program that will solve a problem.
* Object Oriented Paradigm: A type of coding paradigm, which focuses on the creation of objects within the program that work together to create a solution. This process involves creating classes which acts as a template, an iterance of the class would be called an object. A object has 2 characteristics attributes and methods. Attributes are the features of the object, for example if the object was a cat a attribute could be breed. A method is what the object can do, for example if the object was a dog a method could be fetch.
* Procedural Paradigm: A type of coding paradigm, which focuses on calling upon functions to create a solution. These functions are created by the programmer to solve different parts of the problem.
* Event Driven Paradigm: A type of coding paradigm, in which the flow of the program is decided by events such as user actions.
## The Process of Building an Application
#### Step 1: Build a Development Team (or work alone)
The first step is to make a development team, the people you choose should have some experience in coding as it will increase the effeciency of the actual development stage. Alternatively you can choose to work alone, however the workload will be alot higher.
#### Step 2: Wireframing
Wireframing is the process of creating sketches for every possible screen/scene in your app. This helps you plan out how your app will work and what interactions will occur i.e a button that brings you to another screen.
#### Step 3: Design
Next you need to create a design document this should include a design of the user interface and your wireframing skecthes with annotations. You also need to discuss the functionality of you app, you should include in this section the purpose of the app, what interactions will be in the app, what limitations will the app have. It is vital that the functionality section is thoroughly thought out as this is what your development team will be using as reference when constructing the app, so any inaccuracies will lead to mistakes in the app.
#### Step 4: Development
This is where you start to code your app, this process can be very time consuming, but can be even more costly when you make mistakes so make sure you have a very clear and detailed plan and design document.
#### Step 5: Testing
Testing is the process of running your app and seeing if it fufills certain criteria i.e testing a button in your app to see if it bring you to the desired screen. You should make sure you test every aspect of your app to ensure that the whole thing works correctly, you can also test during the development stage to remove any surface errors but you should make sure you do detailed testing once the development is perceived as completed.
#### Step 6: launch
Once you are sure your app is working correctly you then need to release it to the public on your chosen platform, however be aware that some app stores require you to make a payment for them to host your app.
#### Step 7: Maintenance
The final step is to continue to listen to user's feedback, this is so you can remove any found bugs and add any highly requested features.
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
#### Pausing and Editing Code During Rumtime
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
