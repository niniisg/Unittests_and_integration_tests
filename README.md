# Unittests and Integration Tests

## Overview

This project focuses on unit and integration testing. It explains the difference between both, how to perform them, and how to utilize Python's `unittest` framework. Unit testing checks whether individual functions work as expected with various inputs, and integration testing ensures that the system works as a whole when different parts interact.

## Unit Testing

Unit testing involves testing individual functions or methods to ensure they return the expected results. This includes:

- Testing both standard inputs and edge cases (corner cases).
- The unit test should only validate the logic inside the function being tested.
- Any calls to external functions, especially those interacting with networks or databases, should be mocked to avoid side effects.

The goal is to ensure that if everything outside the function works as expected, the function itself will work correctly.

# Unit and Integration Testing

## Overview

This project focuses on unit and integration testing. It explains the difference between both, how to perform them, and how to utilize Python's `unittest` framework. Unit testing checks whether individual functions work as expected with various inputs, and integration testing ensures that the system works as a whole when different parts interact.

## Unit Testing

Unit testing involves testing individual functions or methods to ensure they return the expected results. This includes:

- Testing both standard inputs and edge cases (corner cases).
- The unit test should only validate the logic inside the function being tested.
- Any calls to external functions, especially those interacting with networks or databases, should be mocked to avoid side effects.

The goal is to ensure that if everything outside the function works as expected, the function itself will work correctly.

### Running Unit Tests:

To execute unit tests, use the following command:

`$ python -m unittest path/to/test_file.py`

## Resources

### References:

- unittest — Unit testing framework
- unittest.mock — mock object library
- How to mock a readonly property with mock?
- parameterized
- Memoization

## Learning Objectives

By the end of this project, you should be able to:

- Explain the difference between unit and integration tests.
- Understand common testing patterns such as mocking, parametrizations, and fixtures.

## Requirements

- Your files will be interpreted/compiled on Ubuntu 20.04 LTS using Python 3 (version 3.9).
- All files must end with a new line.
- The first line of every file should be: `#!/usr/bin/env python3`.
- Your code must follow the PEP 8 style guide (version 2.5).
- All files should be executable.
- Every module, class, and function must be documented (use `python3 -c 'print(__import__("my_module").__doc__)'`).
- All functions and coroutines should be type-annotated.
