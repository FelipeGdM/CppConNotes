# CppConNotes

Personal notes about amazing talks from CppCon

## CppCon 2016: Dan Saks “extern c: Talking to C Programmers about C++”

[Video link](https://www.youtube.com/watch?v=D7Sd8A6_fYU)

## CppCon 2017: Bjarne Stroustrup “Learning and Teaching Modern C++”

[Video link](https://www.youtube.com/watch?v=fX2W3nNjJIo)

## CppCon 2017: Kate Gregory “10 Core Guidelines You Need to Start Using Now”

[Video link](https://www.youtube.com/watch?v=XkDEzfpdcSg)

[Slides link](https://github.com/CppCon/CppCon2017/tree/master/Presentations/10%20Core%20Guidelines%20You%20Need%20to%20Start%20Using%20Now)

## CppCon 2018: Kate Gregory “Simplicity: Not Just For Beginners”

[Video link](https://www.youtube.com/watch?v=n0Ak6xtVXno)

[Slides link](https://github.com/CppCon/CppCon2018/tree/master/Presentations/simplicity_not_just_for_beginners)

> If I Had More Time, I Would Have Written a Shorter Letter - _Pascal_

- Simple code == code that explains itself
- Focus on making it easy to use it properly

> Try not to choose simplicity over performance **if** a real choice exists

Compilers and optimizers are amazing and perform the most common optimization operations automatically

**Don't reinvent the wheel** libraries are already tested and document. Functions from standard libraries are zero lines long in terms of cognitive burden

**Abstraction is your friend** and modern C++ provide nice tools to pass abstractions between functions

- `std::tuple`
- `enums`
- `struct`

Prefer struct over `std::tuple` as parameters get names

Early returns are a simple and powerfull refactoring technique - also seen in [CodeAesthetic](https://www.youtube.com/watch?v=CFRhGnuXG-4)

Whenever possible, use `const` and range-for loops

**Don't be an architecture astronaut** - [blog post](https://taskinoor.wordpress.com/2011/09/21/the-abuse-of-design-patterns-in-writing-a-hello-world-program/) about design patterns abuse

> If a write code that anyone can read, what happens to my job?

Coding is a social activity

