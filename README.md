# AirBnB-clone

# Project Description

The AirBnB-clone project is a command-line interface (CLI) implementation of a simplified version of the Airbnb application. It allows users to create, manage, and interact with objects representing various aspects of the Airbnb ecosystem.

# Command Interpreter

# How to Start

To start the AirBnB-clone command interpreter, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/AirBnB_clone.git
2.Once the repository is cloned locate the "console.py" file and run it as follows:

/AirBnB_clone$ ./console.py
When this command is run the following prompt should appear:
(hbnb)
This prompt designates you are in the "HBnB" console. There are a variety of commands available within the console program.
Commands
* create - Creates an instance based on given class

* destroy - Destroys an object based on class and UUID

* show - Shows an object based on class and UUID

* all - Shows all objects the program has access to, or all objects of a given class

* update - Updates existing attributes an object based on class name and UUID

* quit - Exits the program (EOF will as well)
Alternative Syntax
Users are able to issue a number of console command using an alternative syntax:

Usage: <class_name>.<command>([<id>[name_arg value_arg]|[kwargs]])
Advanced syntax is implemented for the following commands:

* all - Shows all objects the program has access to, or all objects of a given class

* count - Return number of object instances by class

* show - Shows an object based on class and UUID

* destroy - Destroys an object based on class and UUID

* update - Updates existing attributes an object based on class name and UUID
examples Example 0: Create an object
Usage: create <class_name>

(hbnb) create BaseModel
(hbnb) create BaseModel
3aa5bcba-efb6-4041-bfe9-3cc9727588f8
(hbnb)
