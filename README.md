# CppConNotes

Personal notes about amazing talks from CppCon

## CppCon 2016: Dan Saks “extern c: Talking to C Programmers about C++”

[Video link](https://www.youtube.com/watch?v=D7Sd8A6_fYU)

## CppCon 2017: Bjarne Stroustrup “Learning and Teaching Modern C++”

[Video link](https://www.youtube.com/watch?v=fX2W3nNjJIo)

> What is not right in teaching programing and how we fix it?

- We are all techers and students and the is no value-neutral teaching

> O processo de ensino-aprendizagem é uma via de mão dupla. De um lado, o professor ensina e aprende e, de outro, o estudante aprende e ensina **Paulo Freire**
.
> The process of teaching and learning is a two-way path. On the one hand, the teacher teaches and learns, on the other hand the student learns and teaches **Paulo Freire**

What is "modern" C++? Canonycally, the revisions of the language post C++11, but it is more than that

C++ is not and never was

- A minor addition to C
- An attempt to become Java
- A random collection of fashionable features

There are **many** ways of using C++

- Teachers *must* choose, it is impossible not to
- Studentes *will* choose, and may disregard much of what is taught

Teach programming, not just language features

- The standard specifies the valid syntax, not the useful parts of the language
- Don't try to teach everything - the hardest part of selecting topics is what to leave out

**Don't reinvent the wheel while teaching!** there are many amazing libraries out there and it is essential to learn how to use them

In the bare language everything is tedious

Don't be too clever

- Simplify stuff - *everything should be made as simple as possible, but not simpler*
- Give a raionale - why we do what we do?

**Use tools** beyond compiler and textbook, a good teacher should show the real experience of programming with C++

- Modern IDE
- Autocompletion
- Build tools

**Don't believe in magic**, a course is just a foundation for more learning, not an end in itself.
Make a connection with hardware, it's abstrations all the way down.

**Modern C++** the good stuff

- Static type safety
- Resource safety
- Abstraction - *zero cost abstractions*
- Encapsulation - classes and beyond
- Generic programming - good use of templates
- Simplicity for most developers - complexity should be hidden in libraries

**CppCoreGuidelines** a concrete way of achieving safer code

**Don't deparate code from explanation** - good examples are key

- Without code, people don't get the ideia
- Without explanation, people don't generalize
- Always give reasons

## CppCon 2017: Kate Gregory “10 Core Guidelines You Need to Start Using Now”

[Video link](https://www.youtube.com/watch?v=XkDEzfpdcSg)

[Slides link](https://github.com/CppCon/CppCon2017/tree/master/Presentations/10%20Core%20Guidelines%20You%20Need%20to%20Start%20Using%20Now)

## CppCon 2018: Kate Gregory “Simplicity: Not Just For Beginners”

[Video link](https://www.youtube.com/watch?v=n0Ak6xtVXno)

[Slides link](https://github.com/CppCon/CppCon2018/tree/master/Presentations/simplicity_not_just_for_beginners)

> If I Had More Time, I Would Have Written a Shorter Letter - *Pascal*

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

> Everything Should Be Made as Simple as Possible, But Not Simpler

