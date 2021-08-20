# Identifiers, Key Words, And Operators
## Python Naming Conventions
### Packages, Modules, Functions, Variables
- snake_case
    - Start with a lowercase letter
    - Separate words with an underscore (_)
### Classes, Exceptions
- PascalCase
    - Start with an uppercase letter
    - Don't seperate individual words
### Constants
- SCREAMING_SNAKE_CASE
    - Should be all uppercase letters
    - Separate words with an underscore(_)
## Python Key Words
### Control Flow
```Python
for # used to create for loops, which allows your code to repeat
in # used when you are referencing one or more objects inside another object, like a list or string
while # used to indicate you want some code to loop until a condition is met
```
### Exceptions
```Python
try # used when something might go wrong and you want to account for it. utilizes except and finally
except # if your code raises any exceptions they can be handled inside an except block
finally # can be added to the end of a try/except sequence or immediately after a try block without any except blocks. A finally block of code will always execute, even if no exceptions are raised
raise # used when code does not execute as intended/expected. Raised exceptions are caught by except blocks
```
### Importing
```Python
from # indicates the location from where you are importing code
import # indicates the package and/or modules you are importing from another location
as # used to set a reference name for the module you are importing
```
### Logical Operators
```Python
is # use this if you are wanting a boolean value that is true when variable A = variable B
is not # use this if you are wanting a boolean value that is true when variable A != variable B
and # use this if you are wanting multiple conditions to be true: variable A = variable B and variable A = variable C
or # use this if you are wanting multiple possible conditions to be true: variable A = variable B or variable A = variable C
if # use this when you want code to run under specific conditions: if variable A = variable B: code
elif # use this when you want code to run under specific conditions that differ from the condition of your if statement: elif variable A = variable C: code. You can have multiple elif blocks chained with an if.
else # use this to run code if neither your if or elif conditions are met. Can only have one else block
True # boolean value, can be used to trigger if/elif blocks. Represents expected conditions being met
False # boolean value, can be used to trigger if/elif blocks. Represents expected conditions not being met
```
### Others
```Python
None
pass
def
class
assert
break
```
### Python Operators
```Python
+ #addition
- #subtraction
/ #divide
* #multiply
** #power of
% #modulous
// #floor division
```
