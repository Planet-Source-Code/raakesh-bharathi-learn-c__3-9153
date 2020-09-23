<div align="center">

## Learn   C


</div>

### Description

Learn the launguage C, with some of my tutorials
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Raakesh Bharathi](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/raakesh-bharathi.md)
**Level**          |Beginner
**User Rating**    |4.3 (13 globes from 3 users)
**Compatibility**  |C, C\+\+ \(general\), Microsoft Visual C\+\+, Borland C\+\+
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__3-32.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/raakesh-bharathi-learn-c__3-9153/archive/master.zip)





### Source Code

Introduction to C Programming
So you want to learn C? We hope to provide you with an easy step by step guide to programming in C. The course is split up into several sections, or lessons,<P>
which include C example programs for you to demonstrate what has been taught. <P>Although the ordering of the sections does not have to be strictly followed,<P> the
sections become progressively more involved and assume background knowledge attained from previous sections.<P> Good Luck!<P>
Before you start:<P><div align=center">
 1.Please read this Introduction.<P>
 2.It is a long course and will take you quite a while to complete.</div> <P>if you have any problems please let us know!. <P><div align=center">
The Course Section Topics:</div><P>
 1.Overview of C.<P>
 a.Why use C? <P>
 b.Uses of C <P>
 c.A Brief History of C <P>
 d.C for Personal Computers <P>
 2.Running C Programs.<P>
 a.Using Microsoft C. <P>
 b.Unix System. <P>
 3.Structure of C Programs.<P>
 a.C's Character Set <P>
 b.The form of a C Program <P>
 c.The layout of C Programs <P>
 d.Preprocessor Directives <P>
 4.Your First Program.<P>
 a.Commenting Programs. <P>
 5.Data Types - Part I.<P>
 a.Integer Number Variables. <P>
 b.Decimal Number Variables.<P>
 c.Character Variables.<P>
 d.Assignment Statement.<P>
 e.Arithmetic Ordering. <P>
 f.Something To Declare. <P>
 6.Input and Output<P>
 a.printf. <P>
 b.The % Format Specifiers.<P>
 c.Formatting Your Output. <P>
 d.scanf. <P>
 7.Control Loops<P>
 a.The while and do while Loops. <P>
 b.Conditions, or Logical Expression. <P>
 c.The for Loop. <P>
 8.Conditional Execution<P>
 a.Program Control - if , if else etc.. <P>
 b.Using break and continue Within Loops. <P>
 c.Select Paths with switch. <P>
 9.Structure and Nesting<P>
 10.Functions and Prototypes<P>
 a.Functions - C's Building Blocks. <P>
 b.Functions and Local Variables. <P>
 c.Getting the Value of Variables into Functions.<P>
 d.Functions and Prototypes. <P>
 e.What is ANSI C?. <P>
 f.Standard Library Functions. <P>
 11.Data Types - Part II<P>
 a.Global Variables.<P>
 b.Constant Data Types. <P>
 12.Arrays<P>
 13.Pointers<P>
 a.Point To Point. <P>
 b.Swap Shop. <P>
 c.Pointers Linked To Arrays. <P>
 14.Strings<P>
 a.Stringing Along. <P>
 b.As easy as... B or C?. <P>
 c.A Sort OF Bubble Program. <P>
 15.Structures<P>
 a.Defining A New Type. <P>
 b.Structures and Functions. <P>
 c.Pointers To Structures. <P>
 d.Malloc. <P>
 e.Structures and Linked Lists. <P>
 f.Structures and C++. <P>
 g.Header Files. <P>
 16.File Handling<P>
 a.Stream Files. <P>
 b.Text File Functions. <P>
 c.Binary File Functions. <P>
 d.File System Functions. <P>
 e.Command Line Parameters. <P>
 17.Recommended Books<P>
 18.Appendix: C's functions<P><P>
You've now reached the end of this tutorial.<P> We have covered a lot of ground - but this has been a first course in C and there is still plenty to learn.<P> However, as long as you keep in
mind that C is an essentially simple language and how new features are built from this simplicity you shouldn't have many problems.<P>
You also need to be aware of the fact that C is a very low-level language and as a result allows programmers<P> to confuse data types and muck around with the bit<P>
patterns of the data in a way that higher level languages would disown!<P> You probably need to make sure that you understand binary and the way that values are<P>
represented to get the best from C.
Overview of C <P>
<P>
Objectives:<P>
This section is designed to give you a general overview of the C programming language. <P>Although much of this section will be expanded in later sections it gives you
a taste of what is to come.<P>
Why use C?:<P>
C has been used successfully for every type of programming problem imaginable from operating systems to spreadsheets to expert systems - and efficient compilers are available for
machines ranging in power from the Apple Macintosh to the Cray supercomputers.<P> The largest measure of C's success seems to be based on purely practical considerations:<P>
 the portability of the compiler; <P>
 the standard library concept; <P>
 a powerful and varied repertoire of operators;<P>
 an elegant syntax; <P>
 ready access to the hardware when needed; <P>
 and the ease with which applications can be optimized by hand-coding isolated procedures
C is often called a "Middle Level" programming language.<P> This is not a reflection on its lack of programming power but more a reflection on its capability to access
the system's low level functions.<P> Most high-level languages (e.g. Fortran) provides everything the programmer might want to do already built into the language.<P> A low
level language (e.g. assembler) provides nothing other than access to the machines basic instruction set.<P> A middle level language, such as C, probably doesn't supply
all the constructs found in high-languages -<P> but it provides you with all the building blocks that you will need to produce the results you want!
<P><P>Uses of C
C was initially used for system development work, in particular the programs that make-up the operating system. Why use C? Mainly because it produces code that runs nearly as fast as
code written in assembly language.<P> Some examples of the use of C might be:<P>
 Operating Systems <P>
 Language Compilers <P>
 Assemblers <P>
 Text Editors <P>
 Print Spoolers <P>
 Network Drivers <P>
 Modern Programs <P>
 Data Bases <P>
 Language Interpreters <P>
 Utilities <P>
In recent years C has been used as a general-purpose language because of its popularity with programmers.<P> It is not the world's easiest language to learn and you
will certainly benifit if you are not learning C as your first programming language!<P> C is trendy (I nearly said sexy) - many well established programmers are switching to
C for all sorts of reasons,<P> but mainly because of the portability that writing standard C programs can offer. <P><P>
A Brief History of C:<P>
C is a general-purpose language which has been closely associated with the UNIX operating system for which it was developed - since the system and most of the programs that run it are
written in C. <P>
Many of the important ideas of C stem from the language BCPL, developed by Martin Richards.<P> The influence of BCPL on C proceeded indirectly through the
language B, which was written by Ken Thompson in 1970 at Bell Labs, for the first UNIX system on a DEC PDP-7.<P> BCPL and B are "typeless" languages whereas C
provides a variety of data types. <P>
In 1972 Dennis Ritchie at Bell Labs writes C and in 1978 the publication of <P>The C Programming Language by Kernighan & Ritchie caused a revolution in the
computing world. <P>
In 1983, the American National Standards Institute (ANSI) established a committee to provide a modern, comprehensive definition of C. The resulting definition, the
ANSI standard, or "ANSI C", was completed late 1988.
A Rough Guide to Programming Languages is available on-line for those of you that are interested. <P><P>
C for Personal Computers:<P>
With regards to personal computers Microsoft C for IBM (or clones) PC's. <P>and Borlands C are seen to be the two most commonly used systems. However, the latest version of Microsoft
C is now considered to be the most powerful and efficient C compiler for personal computers.<P>
Running C Programs <P>
Objectives:<P>
Having read this section you should be able to:<P>
 1.Edit, link and run your C programs <P>
This section is primarily aimed at the beginner who as no or little experience of using compiled languages.<P> We cover the various stages of program development. <P>The basic principles of this
section will apply to what ever C compiler you choose to use, the stages are nearly always the same<P>
The Edit-Compile-Link-Execute Process:<P>
Developing a program in a compiled language such as C requires at least four steps: <P>
 1.editing (or writing) the program
 2.compiling it
 3.linking it
 4.executing it
We will now cover each step separately.<P>
Editing:<P>
You write a computer program with words and symbols that are understandable to human beings.<P> This is the edit part of the development cycle.<P> You type the program directly into a
window on the screen and save the resulting text as a separate file.<P> This is often referred to as the source file (you can read it with the TYPE command in DOS or the cat command in unix).<P>
The custom is that the text of a C program is stored in a f ile with the extension .<P>c for C programming language<P>
Compiling:<P>
You cannot directly execute the source file.<P> To run on any computer system,<P> the source file must be translated into binary numbers understandable to the computer's Central Procesing Unit<P>
(for example, the 80*87 microprocessor).<P> This process produces an intermediate object file - with the extension .obj, the .obj stands for Object.<P>
Linking:<P>
The first question that comes to most peoples minds is Why is linking necessary?<P> The main reason is that many compiled languages come with library rountines which can be added to your
program.<P> Theses routines are written by the manufacturer of the compiler to perform a variety of tasks, from input/output to complicated mathematical functions.<P> In the case of C the standard
input and output functions are contained in a library (stdio.h) so even the most basic program will require a lib rary function.<P> After linking the file extension is .exe which are executable
files.<P>
Executable files:<P>
Thus the text editor produces .<P>c source files, which go to the compiler, which produces .obj object files, which go to the linker, which produces .exe executable file.<P> You can then run
.exe files as you can other applications, simply by typing their names at the DOS prompt or run using windows menu.<P>
Using Microsoft C:<P>
Edit stage: <P>
 Type program in using one of the Microsoft Windows editing packages.<P>
Compile and link: <P>
 Select Building from Make menu.<P> Building option allows you to both compile and link in the same option.<P>
Execute: <P>
 Use the Run menu and select Go option.<P>
Errors: <P>
 First error highlighted.<P> Use Next Error from Search menu for further errors if applicable. <P>
If you get an error message, or you find that the program doesn't work when you finally run it (at least not in the way you anticipated) you will have to go back to the source file - the .c file -
to make changes and go through the whole development process again! <P>
Structure of C Programs <P>
Objectives:<P>
Having completed this section you should know about: <P>
 1.C's character set<P>
 2.C's keywords <P>
 3.the general structure of a C program<P>
 4.that all C statement must end in a ; <P>
 5.that C is a free format language <P>
 6.all C programs us header files that contain standard library functions. <P>
C's Character Set:<P>
C does not use, nor requires the use of, every character found on a modern computer keyboard. <P>The only characters required by the C Programming Language are as follows:<P>
 A - Z<P>
 a -z <P>
 0 - 9 <P>
 space . , : ; ' $ " <P>
 # % & ! _ {} [] () < > | <P>
 + - / * = <P>
The use of most of this set of characters will be dicussed throughout the course.<P>
The form of a C Program:<P>
All C programs will consist of at least one function, but it is usual (when your experience grows) to write a C program that comprises several functions. <P>The only function that has to be
present is the function called main.<P> For more advanced programs the main function will act as a controling function calling other functions in their turn to do the dirty work! The main
function is the first function that is called when your program executes. <P>
C makes use of only 32 keywords which combine with the formal syntax to the form the C programming language.<P> Note that all keywords are written in lower case - C, like UNIX, uses
upper and lowercase text to mean different things. <P>If you are not sure what to use then always use lowercase text in writing your C programs.<P> A keyword may not be used for any other
purposes.<P> For example, you cannot have a variable called auto.<P>
The layout of C Programs:<P>
The general form of a C program is as follows<P> (don't worry about what everything means at the moment - things will be explained later): <P>
preprocessor directives<P>
global declarations<P>
main()<P>
{<P>
 local variables to function main ;<P>
 statements associated with function main ;<P>
}<P>
f1()<P>
{<P>
 local variables to function 1 ;<P>
 statements associated with function 1 ;<P>
}<P>
f2()<P>
{<P>
 local variables to function f2 ;<P>
 statements associated with function 2 ;<P>
}<P>
.<P>
.<P>
.<P>
etc<P>
Note the use of the bracket set () and {}.<P> () are used in conjunction with function names whereas {} are used as to delimit the C statements that are associated with that function.<P> Also note
the semicolon - yes it is there, but you might have missed it! a semicolon (;) is used to terminate C statements. <P>C is a free format language and long statements can be continued, without
truncation, onto the next line.<P> The semicolon informs the C compiler that the end of the statement has been reached.<P> Free format also means that you can add as many spaces as you like to
improve the look of your programs. <P>
A very common mistake made by everyone, who is new to the C programming language, is to miss off the semicolon.<P> The C compiler will concatinate the various lines of the program
together and then tries to understand them - which it will not be able to do.<P> The error message produced by the compiler will relate to a line of you program which could be some distance
from the initial mistake. <P>
Preprocessor Directives:<P>
C is a small language but provides the programmer with all the tools to be able to write powerful programs. <P>Some people don't like C because it is too primitive! Look again at the set of
keywords that comprises the C language and see if you can find a command that allows you to print to the computer's screen the result of, say, a simple calculation.<P> Don't look too hard
because it dosen't exist. <P>
It would be very tedious, for all of us, if everytime we wanted to communicate with the computer we all had to write our own output functions.<P> Fortunately, we do not have to. C uses
libraries of standard functions which are included when we build our programs. <P>For the novice C programmer one of the many questions always asked is does a function already exist for
what I want to do? Only experience will help here but we do include a function listing as part of this course. <P>
All programs you will write will need to communicate to the outside world - I don't think I can think of a program that doesn't need to tell someone an answer. <P>So all our C programs will
need at least one of C's standard libraries which deals with standard inputting and outputting of data. This library is called stdio.h and it is declared in our programs before the main
function.<P> The .h extension indicates that this is a header file. <P>
I have already mentioned that C is a free format language and that you can layout your programs how you want to using as much white space as you like.<P> The only exception are statements
associated with the preprocessor. <P>
All preprocessor directives begin with a # and the must start in the first column.<P> The commonest directive to all C programs is:
#include <stdio.h> <P>
Note the use of the angle brackets (< and >) <P>around the header's name. These indicate that the header file is to be looked for on the system disk which stores the rest of the C program
application. <P>Some text books will show the above statement as follows:<P>
#include "stdio.h" <P>
The double quotes indicate that the current working directory should be searched for the required header file.<P> This will be true when you write your own header files but the standard header
files should always have the angle brackets around them. <P>
NOTE: just to keep you on your toes - preprocessor statements, such as include, DO NOT use semi-colons as delimiters! But don't forget the # must be in the first column. <P>
Thats enough background to C programs - lets get on with our first program which will start to bring together some of the ideas outlined above.<P><P>
<div align="center">Your First Program</div><P>
Objectives:<P>
Yes - it's the ubiquitous <P>"Hello World" program.<P> All your first program is going to do is print the message "Hello World" on the screen.
The program is a short one, to say the least.<P> Here it is:<P>
#include <stdio.h><P>
int main()<P>
{<P>
 printf("Hello World\n");<P>
 return 0;<P>
}<P>
*******THERES A LOT MORE LOOK FOR TEM IN MY NEXT TUTORIAL********

