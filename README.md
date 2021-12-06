# MultiThreadingExamples
"""
Multithreading means that you have several threads running in parallel.
Each thread executes its own code.

Ex:
Actions triggered through clicking a button on a GUI a typically executed in a seperate thread.
This avoids GUI freezing

The module threading provides all the basic functionality you need.

Class Thread - The module provides a class Thread.
To define a thread's activiy you can:
  1. pass a callable object to the constructor of Thread
  2. override the method run() in a subclass
"""
