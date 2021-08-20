# Code Nummies

Code Nummies are bite sized programming challenges, which focus on a specific topic from numerics, computational pyhsics
or computer science. Every Nummy will explain that very topic and provide instructions on how to tackle the problem as
well as some code to get you kickstarted. This includes a set of tests (to verify your solution). Most Code Nummies are
provided in Python and C++.

This is my entry for the #SoME1 [Summer of Math 2021](https://www.3blue1brown.com/blog/some1).

# List of Code Nummies

## Numerics

- [Correlation coefficient](https://github.com/Laguna1989/CodeKata_Numerics_CorrelationCoefficient)
- [Linear Interpolation](https://github.com/Laguna1989/CodeKata_Numerics_LinearInterpolation)
- [Explicit Euler Integration](https://github.com/Laguna1989/CodeKata_Numerics_Euler)
- Numerical root finding
    - [Root finding via the Bisection method](https://github.com/Laguna1989/CodeKata_Numerics_RootFindingWithBisection)
    - [Root finding via the Newton-Raphson method](https://github.com/Laguna1989/CodeKata_Numerics_RootFindingWithNewtonRaphson)
    - [Root finding via the Secant method](https://github.com/Laguna1989/CodeKata_Numerics_RootFindingWithSecant)
- Pseudo Random Number Generators
    - [The RANDU random number generator and why it sucks](https://github.com/Laguna1989/CodeKata_Numerics_Randu)
    - [The Middle Square random number generator and why it sucks](https://github.com/Laguna1989/CodeKata_Numerics_RandomNumbersMiddleSquare)
- The Travelling Salesman Problem
    - [TSP I: Greedy algorithm](https://github.com/Laguna1989/CodeKata_Numerics_TravellingSalesman_Greedy)
    - [TSP II: Simulated annealing](https://github.com/Laguna1989/CodeKata_Numerics_TravellingSalesman_SimulatedAnnealing)

## C++ Topics

- [Smart pointers](https://github.com/Laguna1989/CodeKata_Cpp_SmartPointers)

# Getting Started

## Download a Nummy

You can download a Nummy either via the `Code` -> `Download ZIP` button on github, or
via [git clone](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository).

Most Code Nummies provide a Python and C++ project. You can choose in which language you want to take the problem.

## Python Setup

For Python [PyCharm](https://www.jetbrains.com/de-de/pycharm/) is recommended as an IDE.

* Open the `python` folder in PyCharm.
* Go to settings - `Project: Python` - `Project Structure`. Mark the `src` folder as source, the `tests` folder as
  tests. Close settings.
* In the top right, click on `Edit configuration`. Click on the `+` to create a pytest target. Select `script path` and
  select the `python/tests` folder.
* Press `ctrl + F5` to execute the tests.

## C++ Setup

### Creating the C++ project files with CMake

Navigate to the folder of the Nummy you want to exercise and type

```shell
cmake .
```

in a terminal. CMake supports multiple IDEs, see
the [list of generators](https://cmake.org/cmake/help/latest/manual/cmake-generators.7.html).

### C++ IDEs

* [Windows: Microsoft Visual Studio community edition](https://visualstudio.microsoft.com/de/vs/community/)
* [Windows, Mac, Linux: Clion](https://www.jetbrains.com/de-de/clion/download/#section=windows)
* [Windows, Mac, Linux: Visual Studio code](https://code.visualstudio.com/)
* [Windows, Mac, Linux: Code::Blocks](https://www.codeblocks.org/downloads/binaries/)

# FAQ

## Why Code Nummies?

When learning passively, it happens to me more than often that I say "yes, I would have done it in a similar way". Most
of the time, I am missing out on the crucial parts. The tricky questions will only pop up, once I get my hands dirty and
craft the solution on my own. If you have similar experience, Code Nummies will be very helpful to you. The idea is to
get proper hands-on experience and craft the solution on your own.

To smooth out the experience, the Code Nummies will offer a set of instructions and provide everything to get started.
Tests are included and will guide the implementation. Most Nummies also contain some applications, which will provide
nice results.

## Help, I'm stuck. How do I solve this specific problem?

All Code Nummies have a dedicated branch in git, called `solution`, where you can peek for a solution.

## What does "Code Nummy" mean?

The name is a mashup of "Code Kata" and "Numerics".

## How long will it take me to solve a Code Nummy?

A Code Nummy will take around 30 minutes to complete. Of course individual completion time will vary, depending on the
Nummy difficulty and personal experience. If it takes you longer than an hour, take a step back, get some time off the
screen. Most likely you were stuck in a dead end.

## I have literally no programming experience. What shall I do to cope with this cryptic gibberish?

There are awesome tutorials available on how to get started with (scientific) programming. My personal advice is to just
get started and get your hands dirty. While the Code Nummies relief you of the burden of thinking about most of the
frameworks and test cases, some fundamental understanding of how programming works is unfortunately required. But I am
sure that you can easily get up to speed.

If you have never touched Python nor C++, I suggest to start with Python as it makes starting from scratch easier.
Regardless of the language, you do not have to understand all the internal details, as long as you have a broad
understanding of the algorithm. We are doing math and numerics here, and not strict software development. :)

## Why are the Code Nummies provided in C++ and Python?

C++ is a very powerful, multi-paradigm, portable programming language. Knowing your way around C++ is a very handy
skill. Also, most large scale numerical simulations which run on clusters are written in C++.

Python is an easy to use and portable programming language. It offers numerous packages for various applications. Thus
it is easy to see results quickly and an awesome way to get started.

## I still want to solve a Nummy in [Language of choice]!

There is nothing that will stop you to tackle the problem in matlab, cobol, brainfuck2d or any other language/tool of
your choice. The tests are created with readability in mind, so you should be able to adapt them easily in your
preferred language. Of course, language syntax and some semantic details will be different. However, the transition
should be straightforward.

If you have a solution in a specific tool, please consider creating a Pull Request. Others might be interested as well.
Additionally, it would be great to see the Code Nummies grow by the community.

## I found a typo/bug/issue in a Code Nummy!

Thank you for taking a detailed look at the provided code and instructions. Please create an issue in the respective
repository. If you already know a fix for the issue, please create
a [pull request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
. I am happy to improve the Nummies whenever possible.
