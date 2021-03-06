---
layout: essay
type: essay
title: What is a Computer?
# All dates must be YYYY-MM-DD format!
date: 2016-12-08
labels:
  - Metaprogramming
  - von Neumann
---

What is a Computer?
    To most, a computer is just a machine with various applications and functions. But as we have learned through this past semester, a computer, at its core, is much different. Computers, essentially, compute. However, it is the way in which we program them that allows them to do much more elaborate things. One of the most prominent lines from lecture sums this up this idea, “the basic structure of computer is the foundation; not only the theory of computation, but also the practice of computation”.
    
   The first topic we covered was finite state machines and automata. Through this section, we saw the impact of the Turing machine, and how state machines reflect how computers follow instructions via languages. From formal regular and context free languages we can see how, in its most basic form, to give computers specific instructions. State machines also show a way to provide security. For example, if we allow 1 to represent a security breach in one state, we push that 1 to another state in which the computer can provide another wall of security. In a real life application, perhaps another layer of login information or a firewall. 
    
   Another representation of computers is the von Neumann Computer Architecture. This representation showed the separation of hardware and software which also allows one to understand programmability of a computer. Von Neumann’s big idea also showed that programs and computations are subsets of data. Which brings us back to state machines. Since programs are data, we can represent that data in 1’s and 0’s, and states can represent parts of a program. For example, one part of a program or algorithm, an if statement perhaps, may produce a 1 or 0, which determines the next part of the program to be executed. 
   
   On top of data and programmability, von Neumann’s Computer Architecture also showed that, since programs are just data, programs can serve as input for other programs. When programs serve as input, they are evaluated by a partial evaluator, the input from those programs, or data, then become input to be processed by the universal evaluator, or the cpu. This idea can also be mathematically represented as a composition of functions.
   
   Program evaluators and data services allow for a more mathematical representation of computation. Through data services we see how copying, deletion, and switching functions are represented. We also see in lesson 3 on Computers, a computer consists of data services, programs(that are a subset of data), universal evaluators and partial evaluators. Which brings us to the “Fundamental Theorem of Computation” or “Kleene’s Second Recursion Theorem”. The theorem states that for every computation g, there is a program p such that program p over g can be computed over the universal evaluator u. The related von Neumann diagram also shows that the program p over g is the Kleene fixed point of computation g. 
   
   Next we look at recursion. In programming, we see various computation items such as data types, operations, and program components (i.e. loops). Branching, truth values, loops, arithmetic functions, etc, can all be represented via data services, evaluators and primitive recursion. For example, to add 1 and 1, we take the successor of 1’s predecessor. To display multiplication of numbers x and y, we add x y times. 
   
   As mentioned, loops can be represented via primitive recursion, which is also known as unbounded search and is classified under Computability in lecture. A function f is computable if f(y) outputs a number n, it is required that g(z,y) terminates and outputs a number for all z<n. In other words, a loop must terminate and output a number for each iteration to be valid or computable. 
Now, we have covered data services, primitive recursion, and unbounded search, all of which a language must have to be called “Turing Complete”. All of these topics are indirectly covered in programming classes. When learning Java in our introductory courses, we learn how to do simple arithmetic functions, which are primitive recursive. Loops are also a crucial tool in programming, which is also known as unbounded search. Finally, data services are also covered when learning how to copy or delete items in arrays or other data structures. 

  Next we look at decidability. A predicate p is decidable if it’s computable, its computation always terminates and provides an output. When programs don’t terminate we see the Halting Problem. This is also seen in programming when a program is given a certain input, or the loops are poorly constructed, and the program doesn’t terminate. The program instead outputs garbage or repeatedly prints the last output, which is a common problem for beginning programmers. 
  
  The last topics we covered this semester were compilers and metaprograms. Programmers use these everyday, but it wasn’t until I took this course did I get a better understanding of how they worked and got to see how they can be represented as program evaluators. Earlier, the fact that programs are a subset of data was mentioned. Now it can also be seen that the data from human written programs, or High level programs serve as input to metaprograms to compute the High level language program into  Low level or Machine level language programs. Examples of metaprograms include compilers, program transformers, interpreters, assemblers, code generators, and so forth. 
  
  Once again, metaprograms brings us back to state machines and formal languages. Programmers use languages such as Java and C to write High level programs. Each languages’ respective compiler and assembler turns those programs into Low level then Machine level programs. When we reach the Machine level, the program consists primarily of 1’s and 0’s. As previously mentioned, those numbers represent the output of one part of a program and determine the next section of code, or state, to execute. 
  
  Now we come back to our main question, what is a computer? A computer is, along with everything we just described, a programmable machine. For a machine to be programmable means that a universal computer u can do anything a computer f can do when u is given a program that describes f, as mentioned in lecture 3 on Computer.
  
  Our next question is, what is computer science? Well science is the study of something. In computer science we study computers. However, we don’t study the hardware too much (we leave that to the computer engineers), but focus more on programming computers. Questions we often ask when programming or working on algorithms are, “how can we make this program faster?”, “how can we compute this differently?”, etcetera. As computer scientists, we focus on computing and programming. We study how to improve things via faster computations, or better methods for searching, storing and retrieving data and so forth. Computer science is the study of how to make these programmable machines do the things we want and need them to do. 
  
  Throughout this semester we have covered a variety of computing theories and concepts, all of which can be directly applied to everyday programming and security. We mentioned that computers are just programmable machines, and computer science is the study of programming computers. As simple as this may sound, the amount and level of computation behind programming is what makes computers able to do amazing and complex things. 

Note that the source of all mentioned formal information is lecture, lecture slides, and lecture notes. Some of the formulas may be improperly represented due to special characters. 
