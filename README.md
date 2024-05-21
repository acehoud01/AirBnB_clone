# AirBnB Clone - The Console

## Project Overview

Welcome to the AirBnB Clone project! This project is the first step towards building a full web application similar to AirBnB. The focus of this step is to create a command interpreter to manage AirBnB objects. This command interpreter will be used in subsequent projects involving HTML/CSS templating, database storage, API development, and front-end integration.

## Concept

Before diving into the project, it is essential to understand the AirBnB concept. This project aims to emulate some of the functionalities of the AirBnB platform by allowing the management of various objects, such as Users, Places, Cities, etc., through a command-line interface.

## Objectives

The primary objectives of this project are:

1. **Command Interpreter**: Develop a command interpreter to manage AirBnB objects.
2. **Parent Class**: Create a parent class called `BaseModel` to handle initialization, serialization, and deserialization of future instances.
3. **Serialization/Deserialization**: Implement a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file.
4. **AirBnB Classes**: Develop all necessary classes for AirBnB (User, State, City, Place, etc.) that inherit from `BaseModel`.
5. **Storage Engine**: Create the first abstracted storage engine for the project: File storage.
6. **Unit Tests**: Write unittests to validate all classes and the storage engine.

## Requirements

### Python Scripts

- All files will be interpreted/compiled on Ubuntu 20.04 LTS using Python 3 (version 3.8.5).
- Files must end with a new line.
- The first line of all files should be exactly `#!/usr/bin/python3`.
- A `README.md` file at the root of the project folder is mandatory.
- Code should follow the pycodestyle (version 2.8.*) style guide.
- All files must be executable.
- The length of files will be tested using `wc`.
- Modules should have documentation.
- Classes should have documentation.
- Functions (inside and outside a class) should have documentation.

### Python Unit Tests

- All test files should end with a new line.
- Test files should be inside a folder named `tests`.
- Use the `unittest` module for testing.
- Test files should have the `.py` extension.
- Test files and folders should start with `test_`.
- File organization in the `tests` folder should mirror the project structure.
  - Example: For `models/base_model.py`, unit tests should be in `tests/test_models/test_base_model.py`.
- All tests should be executable using `python3 -m unittest discover tests`.
- Modules should have documentation.
- Classes should have documentation.
- Functions should have documentation.

## Getting Started

To get started with the project, clone the repository and set up your environment.

### Prerequisites

- Python 3.8.5
- `pip` (Python package installer)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/acehoud01/AirBnB_clone.git

