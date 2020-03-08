# llvm-vs-env

This is an opinionated development environment for doing builds and testing of
llvm with Visual Studio code on Windows.

## Requirements

It requires the following software to be installed on the Windows development
system:

- Visual Studio code
- Windows C++ development SDK
- Anaconda 3
- LLVM for Windows (any recent stable build)

Within the Anaconda 3 environment, you will need to install some additional
software:

`
conda install sphinx
`

It requires the following extensions to be installed as part of Visual Studio
Code:

- C/C++
- CMake Tools
- LLVM
- LLVM TableGen
- Python
- reStructuredText
- vscode-clangd

# Use

Clone your llvm-project directory into the llvm-vs-env directory.

You can now use Visual Studio to build llvm with CMake Tools.  