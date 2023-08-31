# GCC Compiler
:wave: Hi there!!!. let's discuss GCC as a compiling tool. :smiley:

# What is GCC
GCC (GNU Compiler Collection) is a compiler for C programming language and it is primarily used to compile source codes written in C to a machine code or executable file.
There are various types of G compilers for different languages, they are as listed:>
- GCC: The C compiler
- G++: The C++ compiler
- Gfortran: The Fortran Compiler
- Gnat: The Ada compiler

GCC provides a range of optimization options, debugging tools, and other features to help developers generate efficient and optimized machine code for different target platforms.

# What is a Compiler
A compiler is a software tool that translates or interprets a source code to a machine code. It translates a high-level programming language into machine code or a lower-level language that can be executed by a Computer's Central Processing Unit (CPU).

It takes human-readable code written in programming languages like C, C++, Java, Python, or more and converts it to a form that a computer can understand and execute.
##### The Compilation process typically involves several steps:
1. Lexical Analysis: The source code is broken down into smaller units called tokens, which are meaningful elements like keywords, identifiers, operators, and constants.

1. Syntax Analysis (Parsing): The tokens are analyzed to determine their grammatical structure and how they relate to each other according to the language's syntax rules. This step constructs a parse tree that represents the program's structure.

1. Semantic Analysis: The compiler checks the program's semantics, such as variable declarations, type compatibility, and function calls. This step ensures that the code makes logical sense.

1. Intermediate Code Generation: In some cases, an intermediate representation of the code is generated. This representation is often more abstract than the final machine code and serves as an intermediate step before generating the actual machine code.

1. Optimization: The compiler may apply various optimizations to the intermediate code to improve the program's performance, such as reducing memory usage or speeding up execution.

1. Code Generation: The compiler generates the actual machine code or assembly code from the optimized intermediate representation. This code is specific to the target architecture or platform on which the program will run.

1. Linking (if necessary): For larger programs, the compiler might generate multiple object files. The linker is responsible for combining these object files, along with any necessary libraries, into a single executable file.

Once the compilation process is complete, the resulting executable file can be executed directly by the computer's CPU without the need for the original source code. This allows software developers to create programs in higher-level languages while still benefiting from the efficiency and speed of machine-level execution.

In addition to compilers, Interpreters typically read and execute code line by line, which can make them slower compared to compiled programs but also provides more flexibility in terms of debugging and dynamic behavior.
#### Steps to form an Executable file in C
1. **Preprocessing**: The preprocessor stage involves handling directives like #include, #define, and conditional compilation.
To Run the preprocessor you need to use this command 'gcc -E filename.c -o filename'
The '-E' command is used to execute the file in the preprocessing stage.
1. **Compilation**: The compilation stage is converting the processed code into the assembly code.
To run the compilation stage, you use this syntax 'gcc -S filename.c -o filname.o
1. Assembler: An assembler is a tool that converts assembly language code into machine code, which is the binary representation of instructions that a computer's CPU can understand and execute. Assemblers perform a critical role in the software development process, as they bridge the gap between human-readable assembly code and the machine-executable code.
1. **Linking**: Linking is the final step in creating an executable file.
It involves combining one or more object files along with any necessary libraries to create a single executable file. The linker (also part of the compiler toolchain) performs this task.
Linking combines object files and libraries, resolves references, and creates the final executable.
These three steps together take your C source code through a series of transformations, resulting in an executable program that can be run on your computer.










