# C Preprocessor Project

A beginner C project that processes a C source file through these stages:
1. Read the input file.
2. Remove comments.
3. Process header inclusion.
4. Replace macros.
5. Write the output to a `.i` file.

## Files

- `main.c` — program entry point and processing sequence.
- `comment_removal.c/.h` — input-file reading and comment removal.
- `header_inclusion.c/.h` — header inclusion logic.
- `macro_replacement.c/.h` — macro replacement logic.
- `test.c` — sample input file.
- `myheader.h` — sample user-defined header.
- `Makefile` — build rules.

## Build

Run these commands from this directory on Linux with GCC and `make` installed:

```bash
make
```

## Run

```bash
./mypreprocessor test.c
```

The program is intended to create `test.i`. The current implementation is a learning project and may need debugging; the build was checked, but its preprocessing output has not been validated as a fully standards-compliant C preprocessor.

## Clean build files

```bash
make clean
```
