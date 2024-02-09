# C Programming

C is a general purpose programming language. It is commonly used in embedded systems projects.

## Compilation

Code for C programs is written by a developer and stored in what is known as a *source file*. The code in the source file is aimed at being readable by humans, but a machine can not run it. Before the code can be run it needs to be converted to another format that the machine accepts. The tool that is responsible for the conversion is known as a *compiler*, and the process is known as *compilation*. The compiler takes the source file as input. From the input the compiler produces output in the form of a file that is ready to be run by a machine. This output from the compiler is termed *executable*.

## Tool Chains

From the previous section on [compilation](#compilation) it can be noted that development is done in chain of events; source file creation, compilation, and finally program execution. Each step requires dedicated tools. The complete set of tools used for development is known as the *tool chain*.

### Basic Tool Chain

A basic tool chain for getting started with C programming development is presented in this section.

As a base there is a need for a general-purpose computer since the actual tool chain is made up of various software that requires a computer run. Type of computer does not matter much, but it should come with a proper keyboard because part of the time developing a C program is spent typing in text.

#### Text Editor

The source files are created in a text editor on the computer. The text must be in *plain text* format which loosely speaking means being made up of only basic letters, numbers, and a limited set of symbols.

There are a lot of different text editors to chose from exactly which one to use is mostly a matter of personal taste and what is commonly used on the type of computer used for development.

All computers tend to come with with a basic text editor already installed by default. But to increase productivity it's in the long run worth the time to learn a more advanced text editor dedicated for programming.

A few examples of text editors suitable for C programming are; Visual Studio Code, Vim, Sublime Text, and Notepad++.

#### Compiler

Popular free compilers for C are GCC and Clang. Both these compilers also have the benefit that they can be run on both Windows and Unix-like machines. Besides Clang and GCC it is also worth mentioning that if developing on a machine with the Windows operating system there is a free variant of Microsoft Visual C++ that can be used to compile C code.

The above are all good options for getting started with C programming. Later on when getting into embedded systems development or professional development there might be need for other C compilers variants that aren't free. Even though there is often ways to develop with free tools also for embedded systems especially if just learning and coding for personal use.

#### Execution

After having written the program in the text editor and being able to compile the code there will be an executable that can be run. It can be so that this executable will be run on the same machine that runs the text editor and compiler, and it's in this case just a matter of starting the executable on the computer.

But it can also be so that the executable is intended to run on another machine that might be very much different from the general purpose computer used for development. Say for example that the program is intended to control a new sewing machine that is under development. In this case the executables first need to be transferred to the sewing machine to fully test the executable.
