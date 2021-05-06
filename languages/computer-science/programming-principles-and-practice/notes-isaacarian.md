# Programming Principles & Practice

### Chapter 1: Computers, People, & Programming

*NOTE: This chapter is entirely introductory, can be skipped unless you haven't even heard of what a computer is.*

- "Our civilization runs on software"
- good software is invisible.
- "Software is a collection of programs running on a computer"
- research relies on computers
- the best programmers spend most of their time **not** coding
- "programming is an intelectually challenging set of skills that are part of many important and interesting disciplines."
	- essential part of the world
- an essential part of programming is user experience
- programming is a subdiscipline of computer science (considered a tool)
- computers are everywhere
- shows examples of computers in shipping, telecommunication, medicine, information, & space 
- ideals for a program
	- correctness and reliability is wanted
	- well-designed and affordable
	- code must be maintainable ("programming is understandable")
- process of building a program
	- Analysis: What's the issue? What does the user want/need/afford? what reliability do we need?
	- Design: How do we solve the issue? Structure of the system? What parts does it consist of? How do these parts communicate with each other/user?
	- Programming: designing solution to the problem and write code that meets all constraints.
	- Testing: make sure the system works correctly under all circumstances.
- programming + testing = implementation
	- testing is crucial

### Chapter 2: Hello, World!
- program: description of instructions given to a computer to follow
- programming: writing and testing these programs
- computers are stupid and literal
- Hello, World! c++ program:
	#include <"std_lib_facilities.h">

	using namespace std;

	int main()
	{
		cout << "Hello, World!\n"; // output "Hello, World!"
		return 0;
	}
- #include <"std\_lib\_facilities.h">
	- calls tools from the file "std\_lib\_facilities.h"
- int main() {}
	- the main *function* of the program
	- every c++ program requires it, and c++ looks for it to start executing
	- "int" is a reserverd word meant to denote an integer *type*
	- "main" is the name of the function
	- () is the list of paraments
	- {} is the body of the function, contains a list of instructions to run the program
- cout << "Hello World!\n";
	- command that outputs "hello world"
	- cout is the standard output stream, characters sent to it using << will output data onto the screen;
	- // is a comment that is not read by the compiler, used to organize and explain code.
- return 0;
	- returns the value 0 from the function (in main() it terminates the program)

- c++ is a compiled language
	- a program called a compiler translates the code into machine readable form
	- "source code":  original text that the programmer writes 
	- "machine code": the machine readable form
- compiler is incredibly exact, so make sure instructions are written correctly
- compile-time errors: errors that occur when translating source code
- a linker program connects several/seperate parts of a program
- link t-time errors: occur during linking
- runtime/logic errors: occur when the program is running
- NOTE: when you compile in an operating system, you get code for THAT operating system, it doesn't run anywhere else
- A library: code written by others that we access using declerations found in an #include command to a file
- decleration: a program statement that specifies how a piece of code can be used
- IDE - interactive development environment, an IDE takes care of compiling and linking, as well as provide services like text editing and debugging
- programing development environment - environment in which to program
- debugging - the act of finding issues in your code
		
	
