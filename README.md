# Overview

This project is a simple **C++ “Hello World” program** designed to verify that my development environment is correctly configured and that I can successfully build, run, and publish software projects using GitHub.  
As a software engineering learner, this exercise helps me practice setting up tools, managing repositories, and following the development and submission process that I will use throughout future projects.  

The goal of this program is straightforward — to display the text **“Hello World”** on the screen, confirming that the code runs successfully. Although basic, this is a fundamental step in building confidence with the programming workflow and development tools.

[Software Demo Video](https://youtu.be/3lXEm77XrmU)

# Development Environment

- **IDE / Editor:** Visual Studio Code  
- **Version Control:** Git & GitHub  
- **Programming Language:** C++  
- **Compiler:** MinGW (g++)  
- **Operating System:** Windows 10  

I created a simple C++ source file named `main.cpp`, compiled it using the terminal, and ran the output to display “Hello World” in the console.  

# Useful Websites

* [C++ Tutorial – W3Schools](https://www.w3schools.com/cpp/)  
* [GitHub Guides – Hello World](https://github.com/olubisiayantoye/Hello-World-Module/)  
* [Markdown Guide](https://www.markdownguide.org/basic-syntax/)  
* [Visual Studio Code Setup for C++](https://code.visualstudio.com/docs/languages/cpp)  
* [YouTube Upload Help](https://support.google.com/youtube/answer/57407)  

# Program Code (Example)

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Hello World! Welcome to my first C++ program." << endl;
    return 0;
}

--  g++ helloworld.cpp -o helloworld.exe
--  ./helloworld.exe    