# C++ Related Code Snippets

Remember to compile binaries safely.

Example:
g++ client.cpp -fPIE -pie -fstack-check=specific -fstack-protector-all -o client -v -shared-libgcc -mtune=generic -march=x86-64
