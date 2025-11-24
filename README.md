# Thread Pool Implementation (C++)

## Project Description
This project implements a simple but functional Thread Pool in C++ using modern multithreading features. A thread pool allows tasks to be queued and executed efficiently by a fixed number of worker threads, improving performance and resource usage in concurrent applications.

## Features
 - Efficiently manages a pool of worker threads to run queued tasks.
 - Task Abstraction. Clean Task class structure for defining and executing units of work.
 - Threads wait for new tasks and shut down cleanly when the pool is destroyed.
 - Concurrent Processing. Real multithreaded execution with minimal overhead.

## Getting Started

### Prerequisites
 - C++17 or newer
 - A compiler such as g++

### Run the Project
Open a terminal in the project root directory and run:

```bash
g++ -std=c++17 -pthread main.cpp Task.cpp ThreadPool.cpp -o threadpool
./threadpool
```
You should see output from multiple worker threads processing tasks.
