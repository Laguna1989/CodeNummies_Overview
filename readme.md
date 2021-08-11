# Code Nummies

Code Nummies are bite sized challenges about a specific topic. Every Nummy will explain that very topic and provide
instructions on how to tackle the problem as well as some code to get you kickstarted. A Code Nummy will take around 30
minutes to complete.

When learning passively, it happens to me more than often that I say "yes, I would have done it in a similar way". Most
of the time, I am missing out on the crucial parts. The tricky questions will only pop up, once I get my hands dirty and
craft a solution on my own. If you have similar experience, Code Nummies will be very helpful to you. The idea is to get
proper hands-on experience and craft a solution on your own.

To smooth out the experience, the Code Nummies will offer a set of instructions and provide us with everything to get
started. Tests are provided and will guide the implementation. Most Nummies also contain some applications, that will
provide nice results.

# List of Code Nummies

## Numerics

- Numerical root finding
  - [Root finding via the Bisection method](https://github.com/Laguna1989/CodeKata_Numerics_RootFindingWithBisection)
  - [Root finding via the Newton-Raphson method](https://github.com/Laguna1989/CodeKata_Numerics_RootFindingWithNewtonRaphson)
  - [Root finding via the Secant method](https://github.com/Laguna1989/CodeKata_Numerics_RootFindingWithSecant)
- [The RANDU random number generator and why it sucks](https://github.com/Laguna1989/CodeKata_Numerics_Randu)
- [Linear Interpolation](https://github.com/Laguna1989/CodeKata_Numerics_LinearInterpolation)
- [Explicit Euler Integration](https://github.com/Laguna1989/CodeKata_Numerics_Euler)

## C++ Topics

- [Smart pointers](https://github.com/Laguna1989/CodeKata_Cpp_SmartPointers)

# Getting Started

## Download a Nummy

You can download a Nummy either via the `Code` -> `Download ZIP` button on github, or
via [git clone](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository).

## Creating the project files with CMake

Navigate to the folder of the Nummy you want to exercise and type

```shell
cmake .
```

in a terminal. CMake supports multiple IDEs, see
the [list of generators](https://cmake.org/cmake/help/latest/manual/cmake-generators.7.html).

## IDEs

* [Windows: Microsoft Visual Studio community edition](https://visualstudio.microsoft.com/de/vs/community/)
* [Windows, Mac, Linux: Clion](https://www.jetbrains.com/de-de/clion/download/#section=windows)
* [Windows, Mac, Linux: Visual Studio code](https://code.visualstudio.com/)
* [Windows, Mac, Linux: Code::Blocks](https://www.codeblocks.org/downloads/binaries/)

# FAQ

## Help, I'm stuck. How do I solve this?

All Code Nummies have a dedicated branch in git, called `solution`, where you can peek for a solution.

## What does "Code Nummy" mean?

The name is a mashup of "Code Kata" and "Numerics".

## Why are the Code Nummies in C++?

C++ is a very powerful, multi-paradigm, portable language. Knowing your way around C++ is a very handy skill. Also, most
large scale numerical simulations which run on clusters are written in C++.

## I still want to solve a Nummy in [Language of choice]!

There is nothing that will stop you to tackle the problem in matlab, python, cobol, brainfuck2d or any other
language/tool of your choice. The tests are created with readability in mind, so you should be able to adapt them easily
in your preferred language. Of course, language syntax and some semantic details will be different. However, the
transition should be straightforward.  
