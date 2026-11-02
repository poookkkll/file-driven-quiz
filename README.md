# file-driven-quiz
A modular terminal-based multiple-choice quiz system built in C demonstrating struct arrays and file handling.
# Console-Based Quiz Management System in C

A lightweight, terminal-based multiple-choice quiz application developed in C. It tests foundational computer science concepts, tracks real-time performance, and persists student results directly into an external log file using file-handling streams.

## Features

- **Direct In-Memory Record Storage**: Employs an array of structures (`struct Question`) to manage questions and multiple-choice options cleanly in memory.
- **Dynamic Case Handling**: Normalizes lowercase user inputs using direct ASCII manipulation.
- **Result Persistence**: Uses standard C file I/O (`fopen` with append mode `"a"`) to log student names, final scores, and percentages to `result.txt` without overwriting historical records.
- **Zero External Dependencies**: Pure standard C library implementation compatible with GCC, Clang, and MSVC.

## Tech Stack

- **Language**: C (C99 standard)
- **Compiler**: GCC / MinGW
- **Tools**: Git, Visual Studio Code

## Getting Started

### Prerequisites

Ensure you have a working C compiler installed:
```bash
gcc --version
