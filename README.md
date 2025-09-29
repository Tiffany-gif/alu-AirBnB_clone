# AirBnB clone - The console 🏠🏠

https://s3.amazonaws.com/alu-intranet.hbtn.io/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUZTW2RLVB%2F20250929%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250929T112951Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=40c9a8f8743cec5a79b116f39f7959689fb9c5aaf4d66df94f6f8d7ebe18a577

# Description of the project

This project is a simple clone of the AirBnB website. The first stage implements a backend interface or console to manage program data(like shell). Console commands allow users to create, update, destroy objects, and manage file storage.

# The console - tasks

- Put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of future instances
- Create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
- Create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
- Create the first abstracted storage engine of the project: File storage.
- Create all unittests to validate all our classes and storage engine

# Description of the command interpreter

The command interpreter helps us to manage the objects of our project by:

- Creating a new object (ex: a new User or a new Place)
- Retrieving an object from a file, a database etc…
- Doing operations on objects (count, compute stats, etc…)
- Updating attributes of an object
- Destroying an object