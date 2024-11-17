AirBnB Clone - The Console

This project is the first step towards building a clone of the AirBnB web application. It focuses on developing a command-line interpreter that handles the creation, management, and persistence of objects used in the AirBnB application.

Description of the Project

The AirBnB Clone project is designed to emulate the backend functionalities of AirBnB. It allows users to:

	•	Create and manipulate objects representing entities such as BaseModel, User, Place, State, City, Amenity, and Review.
	•	Serialize objects to JSON files for persistence and deserialize them back into Python objects.
	•	Perform basic operations like create, retrieve, update, and destroy on these objects using a command interpreter.

The project is modular, meaning additional functionality and object types can be added in future iterations.

Description of the Command Interpreter

The command interpreter is a shell-like program written in Python. It provides a user interface for interacting with the objects in the AirBnB clone project.

Key Features

	•	Interactive Mode: Run the interpreter in a shell-like environment where users can input commands interactively.
	•	Non-Interactive Mode: Run commands via a script.
	•	CRUD Operations: Create, Retrieve, Update, and Delete objects.
	•	Persistent Storage: Automatically saves objects to a JSON file and reloads them on startup.

 Examples

Start the Interpreter

$ ./console.py
(hbnb)

Create a New Instance

(hbnb) create BaseModel
1234-5678-9012

Show an Instance

(hbnb) show BaseModel 1234-5678-9012
[BaseModel] (1234-5678-9012) {'id': '1234-5678-9012', 'created_at': ..., 'updated_at': ...}
