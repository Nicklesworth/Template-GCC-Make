# Template_GCC-Make
Template Makefile project for C/C++ with GCC

## Features
- Two file structure, Makefile is generic, project.mk is project specific
- Automated dependency creation
- All paths flattened in build directory to avoid same file name clashes
- Flexible source inclusion, full directories via SRC_DIRS and single files via CC_SOURCES/CXX_SOURCES
- Basic OS detection to build in different subdirectories (win/macos/linux)
- Basic .vscode folder for use with the C/C++ extension and basic build/launch commands (currently a few fixed paths so you will likely need to tweak)
