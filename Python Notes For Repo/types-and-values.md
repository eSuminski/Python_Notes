# Types
Python handles assigning a type to all variables due to the language being loosely typed. Variables simply have to be declared and then given a value. Adding a colon and then the type after a variable name allows you to tag a variable with the specific type you want the variable to be. This can be useful for remembering what kind of variable you want, but it has no affect on the code. 
### Text
```Python
my_string:str = "this is a string" #String
```
### Numeric
```Python
my_integer:int = 1 #Integer
my_float:float = 1.1 #Float
my_complex:complex = 1j #Complex
```
### Collections
```Python
my_list:list = [1,2,3] #List
my_set:set = {1,2,3} #Set
my_tuple:tuple = (1,2,3) #Tuple
my_range:range = range(7) #Range
my_dictionary:dict = {"key":"value", "another key":"another value"} #Dictionary
```
### Boolean
```Python
my_boolean:bool = True # Boolean
```
### Binary
```Python
my_bytes:bytes = b"byte type" #Bytes
my_bytearray:bytearray = bytearray(7) #BytArray
```