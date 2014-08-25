Mar
===

Learn to implement a toy language.

Dependency
===
	brew install llvm
	echo "export PATH=\$PATH:/usr/local/opt/llvm/bin/" >> ~/.bashrc
	source ~/.bashrc

Build
===

	clang++ -g main.cpp `llvm-config --cppflags --ldflags --libs core jit native` -O3 -o main
