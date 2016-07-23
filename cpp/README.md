# C++ Related Code Snippets

Please do not use any of this code. It is not safe although widely available it is for my own testing of stack canarys.

Remember to compile binaries safely.
Example:

g++ client.cpp -fPIE -pie -fstack-check=specific -fstack-protector-all -o client -v -shared-libgcc -mtune=generic -march=x86-64
