A simple C++ file encryption/decryption tool built to demonstrate and compare **parallel processing** techniques.

## Key Features

This project parallelizes a basic character-shifting cipher using two fundamental OS concurrency models:

* ### Multiprocessing (`fork()`)
    Creates multiple **child processes** to handle file chunks independently. This showcases process management and basic **Inter-Process Communication (IPC)**.

* ### Multithreading (`pthread`)
    Uses **POSIX threads** that operate on a **shared memory segment**, protected by **semaphores** to prevent race conditions. This demonstrates advanced concurrency and synchronization.
