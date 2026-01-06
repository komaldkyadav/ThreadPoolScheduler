Overview

This project implements a Thread Pool Scheduler in C using POSIX threads (pthreads).
A thread pool manages a fixed number of worker threads that execute tasks from a shared queue, improving performance by avoiding frequent thread creation and destruction.

This scheduler is useful for:

1. Concurrent task execution

2. Server-side request handling

3. Parallel computation

4. Resource-efficient multithreading

Features

1. Fixed-size thread pool

2. Task queue with FIFO scheduling

3. Thread-safe synchronization using mutexes and condition variables

4. Graceful shutdown of worker threads

5. Lightweight and portable (POSIX compliant)
