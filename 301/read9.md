# Functional Programming Concepts
What is functional programming?

 Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

# What is a pure function and how do we know if something is a pure function?

It returns the same result if given the same arguments 

It does not cause any observable side effects

# What are the benefits of a pure function?

is important to make our functions more consistent and predictable. The idea is to build a new collection with all absolute values.

# What is Referential transparency?

if a function consistently yields the same result for the same input, it is referentially transparent.
we can said pure functions + immutable data = referential transparency

module
A module is a software component or part of a program that contains one or more routines. One or more independently developed modules make up a program.


# How do we bring another module into the file the we are working in? 

we need to import the module. we will use the require keyword at the top of the file. The result of require is then stored in a variable which is used to invoke the functions using the dot notation

# How to create your own Node. js module

Download & install Node. js. ...
Create a Node project. Create an empty project using the following commands: mkdir MyCoolModule. ...
Write your module.

 There should now be a package. ...
Publish the module to NPM (Node Package Manager) ...
