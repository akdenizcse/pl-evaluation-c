C++

- History of the language: who/when invented it, which languages influenced it, etc.

The C++ programming language has a history going back to 1979, when Bjarne Stroustrup was doing work for his Ph.D. thesis. Firstly, it was called "C with Classes". In 1983, the name of the language was changed from "C with Classes" to C++ because of many new features were added after the classes.
C was general-purpose, fast, portable and widely used. 
The Simula 67 language is regarded as the first language to support the object-oriented programming paradigm
Single-line comments using two forward slashes which is a feature taken from the language BCPL
Other languages also influenced this new language, including ALGOL 68, Ada, CLU and ML.

- Why was it invented

The Simula 67 language had features that were very helpful for large software development, but the language was too slow for practical use. BCPL is fast but too low-level to be suitable for large software development.C was chosen because it was general-purpose, fast, portable and widely used. However, C does not support object oriented programming. 

- When/why shall we use it

It is widely used in building real-time, image processing, mobile sensor applications, and visual effects, modeling which is mainly coded in C++. It allows procedural programming for intensive functions of CPU and to provide control over hardware, and this language is very fast because of which it is widely used in developing different games or in gaming engines. It mainly used in developing the suites of a game tool. This language is also used for developing database software or open-source database software. The example for this is MySQL, which is one of the most popular database management software and widely used in organizations or among the developers. Most of the compilers mainly written in C++ language only. The compilers that are used for compiling other languages like C#, Java, etc. mainly written in C++ only. It is also used in developing these languages as well as C++ is platform-independent and able to create a variety of software.


- How to setup an environment to use it in different platforms

Linux: You have to first run the below command from your Linux terminal window:
sudo apt-get install GCC
This command will install the GCC compiler on your system. You may also run the below command:
sudo apt-get install build-essential

Windows: There are lots of IDE available for windows operating system which you can use to work easily with C++ programming language. One of the popular IDE is Code::Blocks.

Mac OS : If you are a Mac user,you have to download Xcode. To download Xcode you have to visit the apple website or you can search it on apple app store.

- Example codes
```C++

#include<iostream>
 
using namespace std;
  
int main()
{
    int i, number, first = 0, second = 1, next;
    first = 0;
    second = 1;
    cout << "Write a number: "; 
    cin >> number;
    cout << "Fibonacci series: \n";
     
    for(i = 0; i < number; i++)
    {
        cout << "\n" << first;
        next = first + second;
        first = second;
        second = next;
    }
    return 0;
}
```

- Things that are specific to this language?

C++ language offers many paradigm choices.C++ offers remarkable support for procedural, generic, and object-oriented programming paradigms, with many other paradigms being possible as well. 

