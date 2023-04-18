# pfcppStudy
practicing proffessional cpp book

# Standard Library
    comments, module import (include), main(), I/O stream
## Hello World example
### Build process
1. preprocess
    processs meta data from source code
2. complie
    compile source code into machine code, object file (.o)
3. link
    link multiple object files into application
### directive
    expressions for preprocess
    starts with #
#### examples
    #include [file]
    #define [key] [value]
    #ifdef [key] / #endif
    #ifndef [key] / #endif
    #pragma [xyz]
##### pragma examples
    #pragma once -> define header with duplication check
### main()
    int main(int argc, char* argv[])
    argv[0] -> name of program
### I/O stream
    <format> in C++ 20
    printf, scanf -> type safety insecure
## namespace
    space to resolve name collision problem
## 