# Tiny Programs: Rosetta code for implementations

Learning a new language can be hard. Developers go to "Hello World"
but this is so trivial a program so as to be almost useless.

This project is a collection of tiny programs that may help you learn
a language. It is similar to Rosetta Code except that all programs
here will be *implementations* and not library calls.

Implementations are opinionated and simple, but not necessarily
idiomatic. Tests are in place for all implementations but they are not
necessarily 100% bug-free.

# Programs

* [Brainfuck](./Brainfuck): A complete Brainfuck implementation
* [UUIDv4](./UUIDv4): A UUIDv4 generator
* [AATree](./AATree): A generic, balanced binary tree
* Potential:
  * Lisp: A tree-walking s-expression interpreter capable of running a fibonacci function
  * JQ: A tiny JQ clone
  * HTTP: An HTTP server from UNIX sockets

# Contributing an implementation

A few rules:

1. Keep it simple and readable.
1. This isn't code golfing.
1. Do not copy any existing code. Write the program from scratch. See
   rule 1.
1. Use existing implementations in this project as guidelines. Use the
   same or similar algorithms and data structures. See rule 1.
1. Avoid programming patterns and object-oriented design and
   functional programming for the sake of patterns and OOP and FP. See
   rule 1.
1. Avoid unnecessarily complex syntax, even if the complex syntax is
   more idiomatic in the language. See rule 1.
1. Copy program.yaml and implement the `prepare` and `run` settings so
   that your implementation is automatically tested in Github Actions.
1. Definitely no 3rd-party libraries. And definitely not builtin
   libraries if they implement the entirety of the program.

Ultimately, Phil is the BDFL and reserves the right to be picky. :)

## Call for languages

* Ada
* FreePascal
* FreeBASIC
* R
* Octave
* Common Lisp
* Swift
* Kotlin
* Scala
* Clojure
* Lua
* C++
* D
* Standard ML
* OCaml

# Discussion

Questions? Ideas? Suggestions? Bring it up in the #hacking channel on
[discord.multiprocess.io](https://discord.multiprocess.io).
