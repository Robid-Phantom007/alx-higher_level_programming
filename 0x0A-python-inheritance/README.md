# Python - Inheritance

## General :page:
* Why Python programming is awesome
* What is a superclass, baseclass or parentclass
* What is a subclass
* How to list all attributes and methods of a class or instance
* When can an instance have new attributes
* How to inherit class from another
* How to define a class with multiple base classes
* What is the default class every class inherit from
* How to override a method or attribute inherited from the base class
* Which attributes or methods are available by heritage to subclasses
* What is the purpose of inheritance
* What are, when and how to use isinstance, issubclass, type and super built-in functions

## Requirements :page:
### Python Scripts
* Allowed editors: vi, vim, emacs
* All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
* All your files should end with a new line
* The first line of all your files should be exactly #!/usr/bin/python3
* A README.md file, at the root of the folder of the project, is mandatory
* Your code should use the pycodestyle (version 2.8.*)
* All your files must be executable
* The length of your files will be tested using wc

### Python Test Cases
* Allowed editors: vi, vim, emacs
* All your files should end with a new line
* All your test files should be inside a folder tests
* All your test files should be text files (extension: .txt)
* All your tests should be executed by using this command: python3 -m doctest ./tests/*
* All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
* All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
* All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
* A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)
* We strongly encourage you to work together on test cases, so that you don’t miss any edge case

### Documentation
* Do not use the works import or from inside your comments, the checker will think you try to import some modules

## Files :heavy_check_mark:
| Filename | Description |
| -------- | ----------- |
| `0-lookup.py` | Function that returns the list of available attributes and methods of an object |
| `1-my_list.py` | Class `MyList` that inhertis from `list` |
| `2-is_same_class.py` | Function that returns `True` if the object is exactly an instance of the specified class; otherwise `False` |
| `3-is_kind_of_class.py` | Function that returns `True` if the object is an instance of, or if the object is an instance of a class that inherited from, the specified class |
| `4-inherits_from.py` | Function that returns `True` if the object is an instance of a class that inherited from the specified class |
| `5-base_geometry.py` | Empty class `BaseGeometry` |
| `6-base_geometry.py` | Class `BaseGeometry` with public instance method `def area(self):` |
| `7-base_geometry.py` | Class `BaseGeometry` with public instance method that verifies if the input arg is an integer |
| `8-rectangle.py` | Class `Rectangle` that inhertis from `BaseGeometry` |
| `9-rectangle.py` | Class `Rectangle` that inhertis from `BaseGeometry`, with `area()` method implemented |
| `10-square.py` | Class `Square` that inherits from `Rectangle` |
| `11-square.py` | Class `Square` that inherits from `Rectangle`, with `str()` method |
| `100-my_int.py` | Class `MyInt` that inhertis from `int`. Its `==` and `!=` operators are inverted |
| `101-add_attribute.py` | Function that adds a new attribute to an object if it's possible |
