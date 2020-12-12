# cpp_test

g++ -E test.cpp -o test.ii => The preprocessor is an important part of the compiler

g++ -S test.ii -o test.s   => g++ compiler

as test.s -o test.o        => A tool called "assembler" converts the assembly code into machine code

g++ test.o -o test         => Linker // ./test => Hello, Hacker!
