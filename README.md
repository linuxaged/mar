Mar
===

Learn to implement a toy language.

Build
===

	clang++ -g -O3 main.cpp `llvm-config --cppflags --ldflags --libs core` -o main
