##C++ JIT Interpreter
This interpreter aims to provide a JIT compiler for a subset of C++11, with support for features such as
lambdas and templates.

##Invocation
There is no entrypoint, and definitions are pre-processed by the JIT compiler differently
to its compiled counterpart.

##Rationale
- Users shouldn't have to pre-process, compile and link their respective programs to verify their understanding
of C++11 language features.
- The C++ syntax is favoured by many, and therefore familiar to most developers.