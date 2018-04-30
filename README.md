# Glossary-of-Tech-Terms
## Programming Terms ##
* Algorithm: A set of rules/instructions that are used to solve a certain problem, in most cases the algorithm is run by a computer to create a program that will solve a problem or reach a certain goal. A computer will follow these instructions in the same way every time the algorithm is run by the computer, unless changes to the actual algorithm are made.

* Object Oriented Paradigm: A type of coding paradigm, which focuses on the creation of objects within the program that work together to create a solution. This process involves creating classes which acts as a template, an iterance of the class would be called an object. A object has 2 characteristics attributes and methods. Attributes are the features of the object, for example if the object was a cat a attribute could be breed. A method is what the object can do, for example if the object was a dog a method could be fetch. This paradigm is used to model behaviour, this is because each class acts as its own program, containing different variables and functions. Then, from the same class, objects with varying attributes can be created, which can be used to solve different problems within the solution.

* Procedural Paradigm: A type of coding paradigm, which focuses on calling upon functions to create a solution. These functions are created by the programmer to solve different parts of the problem. A procedural paradigm allows a programmer to break down the problem into sub problems so that they can create a function for each sub problem, this paradigm also allows a programmer to use a function for different sections of their code.

* Event Driven Paradigm: A type of coding paradigm, in which the flow of the program is decided by events such as user actions. The characteristics of an event driven paradigm are event handlers which are designed to run a certain function when a certain event occurs, an example of a event handler is when a key is pressed on a keyboard on a word document and the key pressed is printed in the document. Another characteristic is trigger functions, trigger functions decide what function needs to be run when a event occurs, trigger functions decide upon which event handler to use for the event, for example when a proximity sensor detects someone nearby, that information is relayed back to the system running the door where the trigger function will run the event handler which opens the door. Event driven programming is useful for when creating software which requires a large amount of user input (for example a phone app) as the programmer can plan out all the events that could occur and create event handlers and trigger functions for each possible event.
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
Next you must try and reproduce the bug, creating a snapshot of the state of the code when the bug appears (variable values, etc.)and what function is being run.
#### Step 4: Analyze the Snapshot
Begin to look at the functions being run around the time when the bug occurs and look for the individual function(s) that could be causing the bug. Once you have found the section of code that is causing the bug you can begin to think of possible solutions to fix the bug.
#### Step 5: Test the Solution(s)
Once you have implemented your solution into the code, you need to test it. If the solution fixes the bug and creates no new bugs then the solution was successful. If the solution does not work or creates new errors, you will need to repeat these steps. A possible issue could be you created a snapshot at the wrong point of the code runtime.
## The Debugging Facilities Available in the IDE
The debugging process can be less time consuming when using an IDE, this is because it provides a debugger with many different facilities to aid in discovering and fixing errors, such as
#### Step Over,Step Into and Step Out Commands
These commands help the programmer jump to and run, seperate functions within their code. The step into command jumps to the next function within the code, the step over command skips the next function and moves onto the function after it, finally the step out command leaves the current function being run. These commands help with debugging as it helps the programmer test different parts of their code, without having to run the whole code or disturb certain parts of the code, this is especially helpful when working with large amounts of code.
#### Pausing and Editing Code During Runtime
Some debuggers can allow you to pause your code while it is running this can allow you to edit the code, allowing you to see realtime results of the changes you make. This allows you to find solutions to bugs in your code quicker as you can more effeciently test different solutions.
#### Allows Variable States to be Seen During Runtime
Most IDEs also allow the programmer to observe the current value of any variable while the program is running, this allows the programmer to know in what parts of the program variables are being changed and check if any variables are being changed to a unexpected value.
## The Steps from Writing Code to Execution
### Step 1: Write your Code
Before anything can be run, you must first write out your code, you can either do this in a .txt document or by using an IDE (integrated development environment). The type of code you write in is high level code, which is code that is written in a language close to the english language so it is easier to understand. However a computer cannot understand high level code and will need to translate the high level code to machine code.
#### Step 2: Using an Interpreter/Compiler
A computer cannot understand the code you have written as the langauge you wrote it in is a high-level language, a processor can only understand machine code. So first, the computer must translate the high-level code to machine code, to do this the computer uses an interpreter or a compiler. An interpreter translates one line of code and then executes it one at a time, whereas a compiler translates the whole source code before executing it. All IDEs have a interpreter/compiler implemented in it, so that your code can be translated and run within the IDE.
#### Step 3: Obtain Memory
All processes in a computer require memory, so before any lines are executed the operating system of the computer must allocate a certain amount of memory for the process of running your code before it can be ran by the processor. Once the memory has been allocated the computer can then run the code, or create a virtual machine where the code can be run in, this depends on the programming language you are using.
#### Step 4: Run Code
The processor runs the stored machine code, and therefore runs your written high-level code.
## How Technical Solutions Can be Compared
The following factors are judged when comparing technical solutions:
* Robustness: Robustness refers to how resilient a peice of code is, meaning that the code has minimal bugs and crashes extremely rarely. Robustness also refers to a softwares ability to withstand erroneous input, which means inputs that have the ability to cause issues to the software, i.e. a user inputting a integer when the software is expecting a string.
* Efficiency: Efficiency refers to the speed of the runtime of the execution of software, meaning how long the software takes to give the desired solution. Speed of runtime also refers to how long the actual source code is, i.e software with a minimal amount of lines of source code are more effecient that software with large of amounts of lines of source code.
* Fitness: This refers to whether or not the solution fufils its intended purpose, or if it is being used for a different purpose.
* Cost of Software: This refers to how much the consumer would have to pay for the software, being a annual cost or a one time cost. Software needs to be priced fairly for it to gain popularity in its respective market.
* Reliability: This refers to the chances that the program will complete the same purpose each time it is used, a reliable system will always do what it is intended to do with ease.
* Support: If something goes wrong with the software, how many people can help solve the user's issue or what tools are available  to the user to help fix the issue.
* Maturity: This refers to the version of the technical solution, it is risky for any company to use version 1.0 of anything, as companies are pressed to release products before they are ready. So it is important to release new versions of software to ensure that the software works correctly and to add new requested features.
## The Importance of Team Dynamics 
Team dynamics are the aspects that affect the relationship between members of a team and how it affects how the team functions together. Good team dynamics start with an effective project manager, a good manager needs to define the nature of the group through positive guidance and effective management of tasks. Effective communication is an important team dynamic, the project leader must give directions and tasks clearly, to make sure that every member fully understands the task they are given. The members of the team need to feel comfortable so that they can relay problems and questions to each other and the manager. Motivation is also a key aspect of team dynamics, as motivated members are eager to contribute towards the project, whereas unmotivated members may only produce just enough work to avoid scrutiny jeprodising the success of the project. To ensure motivation within your team use incetives to encourage work, for example give rewards to members of the team that achieve their tasks ahead of the deadline. Finally effeciency is a very important team dynamic as it allows each member to work to their fullest.
## How to Address Software Requirements in Projects 
To address the requirements when starting a project we use the SCRUM model to plan and break down requirements. The first part of the model is to come up with the overall goal of the project, in SCRUM, this is called the initiative. Once the overall goal has been decided it is broken down into large bodies of work called epics in SCRUM, the epics are then broken down further. The epics are broken down into short requirements/ requests written from the perspective of the end user, in SCRUM, these are called user stories and are the final stage of planning out the requirements of the project.

![SCRUM](https://github.com/SDearing/Glossary-of-Tech-Terms/blob/master/assets/SCRUM.png)
## Analysis of Common Features of an IDE
### Code Editor
One of the main functions of an IDE is that it provides an environment where the user can write code, this is called a shell. The code editor allows a user to write, edit and save a documentation of code and contains features to assist the user further when constructing their code. These include:
* Auto-completion: This feature guesses what function you are going to write, as you begin to write it, and suggests possible functions to finish the line. This feature also suggests any variable names if you begin to write a declared variable. The purpose of this feature is to save time for the programmer while they are writing code and it ensures that there will be no typos when writing variables and functions which will reduce the likelihood of syntax errors in their code.
* Syntax Highlighting: This feature displays source code, in different colours depending on the category of the text in the language, for example a funtion in a IDE may be highlighted blue and comments may be highlighted red. The purpose of this feature is to allow the programmer to easily read their code, which is especially helpful when dealing with a large amount of code.

## Research on the Use of Different Problem-Solving Techniques in the Design and Delivery of an Event
### Abstraction
Abstraction is the method of taking a solution, and removing unnecessary details from a solution so that it can be applied to more problems. For example the London Underground Map uses abstraction by removing details such as the address of stations and what locations are around the station, and instead solely focuses on the the train line the station is on, what stations are on the train line, this allows the map to be used to navigate the train line, and by abstracting details from the map allows for very effective navigation of any train line for any user. Abstraction is very useful in the design of an event as it allows the designer to remove any unnecessary details from the plan and allows the designer to focus on the key details of a problem. Abstraction is also useful in the delivery on an event as it allows the given event to solve its purpose effectively and effeciently, as details are being ignored to focus on the larger picture of the event.
### Decomposition
Decomposition is the process of breaking down a problem into smaller sub-problems that are easier to solve, this allows a project designer to fully understand the main problem and design smaller tasks which could be treated as milestones of completion for the initial problem. An example of decomposition is when you are making a cup of tea you break down the act of 'making a cup of tea' into several steps; such as get the mug, boil the water, add tea bag to the mug, add milk, sugar etc. Decomposition is useful in the delivery of an event, as depending on the accuracy of the decomposition, this problem solving technique ensures that the problem will be solved fully by the given solution if it fulfils every sub-problem.
