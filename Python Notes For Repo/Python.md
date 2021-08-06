## Python

[Python](https://www.python.org/about/) is an Open-source **interpreted** programing language designed for readability and ease of use. It is a powerful language that provides a great entry-point into programming, and it is used by many successful companies (Google, Facebook, Spotify, Netflix, Dropbox, and more). 

There are a few key factors that make the language easy to use, and one of them is automatic memory management. As a **high level language**, Python automates memory allocation for the developer, leaving them free to focus on creating functional code. This includes automated garbage collection: when a developer's code is no longer needed, Python will automatically remove it from memory.

**Dynamic typing** is another feature that makes Python easy to use. Creating variables and assigning them values is as easy as:
```Python
name = "name"
number = 10
big_number = 1247342832468323483
```
Python will automatically assign a type to a declared value based upon the value assigned to it. Once assigned, this value cannot be coerced into a different type because Python is a **strongly typed**:
```Python
name = "name"
number = 10
print(name + number) #this will cause an error
```
Lastly, Python utilizes **just in time compilation**. This means Python applications, instead of having all their code compiled and then having the application run, will compile and run code line-by-line. This is different from languages like C++ and Java.


## Pip

**Pip** is a package installation software that is provided with Python. Developers can use it to download packages from the internet and integrate them into their projects.

## PyPi

[PyPi](https://pypi.org) is the main repository of Python packages on the web. Pip is easily able to take code from here and add it to a Python project.

## Venv

Because it is common practice to download packages from PyPi for projects, developers can very quickly overwhelm themselves with packages of code from the repository they don't need. It is reccomended to create **virtual environments** to avoid this. Pip can manage this with the terminal command:`-m venv /path/to/new/virtual/environment`.

## Installation

1. Go to the download section on the [Python](https://www.python.org/downloads/) website and select the version that matches your OS.
    - You can confirm your download was successful by running the command `py --version` in a Command Shell. Pip is included with your Python download, so if you successfully installed Python you also have pip.

## References

[Python Documentation](https://docs.python.org/3/)