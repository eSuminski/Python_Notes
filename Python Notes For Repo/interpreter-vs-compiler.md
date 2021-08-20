# Interpreter vs Compiler
All programming languages have the same problem: they need another source to allow them to be executed. This can be handled by an interpreter or compiler.
### Compiler
Compilers are software that take the entirety of provided sourcecode and translate it into machine language. The compiler starts by parsing the content of the source code and building an object file (not related to OOP). Assuming the compiler has no problems creating the object file, it then proceeds to create an executable file. This completes the process.
### Interpreter
Interpreters are software that read through sourcode, pre-compiled code, and scripts, and execute them. This allows for easier debugging because it is easier to track where compilation fails, but it also makes it slower to run. Unlike a compiler, interpreters don't create an intermediate object file: this makes interpreters more memory intensive. It also does not create an executable file: it runs the code it reads directly.

#### Python Interpreters
- [CPython](https://github.com/python/cpython)
    - default compiler provided from the official Python website
- [PyPy](https://pypy.org/)
    - faster than CPython, doesn't support CPython extensions
- [Stackless Python](https://github.com/stackless-dev/stackless)
    - avoids C call stack
- [Jython](https://hg.python.org/jython)
    - can convert Python into Java byte code
- [IronPython](https://ironpython.net/)
    - allows devlopers to use Python and .NET together