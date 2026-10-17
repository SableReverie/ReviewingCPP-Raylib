# CppReview

A small C++ starter project containing a program that prints `Hello World!`.

## Requirements

- A C++ compiler such as GCC, Clang, or MSVC

## Build and run

From this folder, compile the source:

```sh
g++ -std=c++11 -Wall -Wextra -pedantic print.cpp -o print
```

Run it on macOS or Linux:

```sh
./print
```

On Windows, run the generated executable:

```powershell
.\print.exe
```

Expected output:

```text
Hello World!
```

## Project files

- `print.cpp` — program entry point and console output
- `.vscode/tasks.json` — VS Code build task for the active C++ file
