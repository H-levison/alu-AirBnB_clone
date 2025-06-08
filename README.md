# AirBnB Clone - The Console

Welcome to the first step towards building a full-stack web application: the **AirBnB Clone**. This project lays the foundation for a simplified clone of the AirBnB platform, focusing on implementing a command interpreter that will eventually link with future components like the front-end, database, and RESTful API.

---

## Project Description

This first phase is centered around creating a **command-line interpreter** that manages the entire application's functionality in both interactive and non-interactive modes. The command interpreter will handle:

- Creating and managing data models (`User`, `Place`, `City`, `State`, `Amenity`, `Review`)
- Serialization and deserialization of models to and from JSON
- File storage using a custom engine
- Unit tests for ensuring code quality and integrity

This foundation will be reused and expanded upon in future stages of the AirBnB clone.

---

## Features Implemented

- **BaseModel**: A parent class that handles initialization, serialization to dictionary/JSON, and deserialization.
- **Command Interpreter**: Interactive shell with basic commands like `create`, `show`, `destroy`, `all`, `update`, `quit`, and `EOF`.
- **Model Classes**: `User`, `State`, `City`, `Place`, `Amenity`, and `Review` – all inheriting from `BaseModel`.
- **File Storage Engine**: Abstracted storage system using JSON file for persistence.
- **Unit Tests**: Covering all classes and storage functionality using `unittest`.

---

## Command Interpreter Description

The command interpreter allows users to create and manage object instances through a shell interface. It supports:

- **Interactive mode**: Start the console and interact with it directly.
- **Non-interactive mode**: Execute commands via file or piped input, ideal for scripting and automation.

---

## How to Start the Command Interpreter

Ensure you have Python 3 installed on your machine. Then, make the console script executable:

```bash
chmod +x console.py

```

## AUTHORS
Please see the AUTHORS file for a full list of contributors to this project.