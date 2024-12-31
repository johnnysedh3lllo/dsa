# Brief History of C++

Before C++, there was **C**, a general-purpose, high-level programming language created by **Dennis Ritchie** in _1972_ at Bell
Telephone Laboratories (often called, Bell Labs).

One of Dennis' goals was to created a language that was self-reliant. Given that most of the languages at the time relied on other languages or external tools to build their key features, for example:

- **COBOL**, **FORTRAN** and **ALGOL** depended on Assembly as compilers for both languages where written in Assembly Language.
- **Pascal** having it's compiler initially written in Assembly, while utilizing other languages and tools
- Other languages writing their features in Machine Language _(hmmm, must've been rough)_.

The issue with basing technology on other technologies is introduction of dependency, i.e: dependency on other technologies. When features were written in Assembly, they had to rewritten to support different hardware, given that Assembly is hardware-specific (assembly code written for one hardware cannot work for other hardware), and features written in Machine Language were error-prone given the herculean task of writing error-free 1's and 0's.

To achieve C's self-reliance, Dennis employed a technique formally called **"Bootstrapping"**. In the context of programming languages,
bootstrapping refers to the process of writing a program in one language, then rewriting it in the same language (or another programming language) to improve it or make it self-sustaining.

So with this technique, the original compiler for C was written in Assembly. Once functional, the compiler was then **rewritten in C**, enabling it to **generate machine code** for the next version, making C **the first high-level programming language to achieve true self-reliance**. This meant that libraries and tools for the language could be written in C itself, without depending on other tools or languages. Additionally, C gave programmers the flexibility to write code that could be easily compiled to support various hardware platforms—pretty cool!

![C code compilation Process](process.png)
**Note: this may be moved later**
