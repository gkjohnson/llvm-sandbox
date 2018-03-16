# LLVM Notes

## Vocabulary

#### LLVM Front End

Compiler that targets LLVM IR, such as Clang for C / C++, Numba or py2llvm for Python.

#### LLVM Back End

Compiler that takes LLVM IR or Bitcode and outputs code or binary for the target environment. Emscripten, for example, will build LLVM Bitcode to javascript.
