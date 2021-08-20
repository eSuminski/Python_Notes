|Question|Answer|
|--------|------|
|What are the Python primitives?| There are none: everything is an object in Python|
|What are classes in Python| They are blueprints for creating objects. They can have variables, methods, and they can inherit from other classes|
|Does python support multiple inheritance?| Yes it does|
|How does a class inherit from another class?| You add the parent class as a parameter in the class declaration|
|How are Python class constructors made?| You use the \_\_init\_\_() dunder method. Child classes inherit their parent constructor unless one is made for them. If the child class has their own constructor they can still access the methods and properties from the parent constructor by either calling the class constructor (parent.\_\_init\_\_(self, parameters) or by substituting super() for the parent class|
|Can Python constructors be given default values?| Yes, you add it as part of the parameter (def\_\_init\_\_(self, a_string = "default", a_number = 0))|
|What are the differences between class and instance variables?| Class variables are shared among all instances of the class, and are accessed by calling the class name, using the dot operator, and referencing the variable (MyClass.class_variable). Instance variables are unique to each object and are accessed by calling the class reference, using the dot operator, and then referencing the variable (instance_of_my_class.instance_variable). Inside the class description you would use self instead of a reference to indicate an instance variable (self.instance_variable).|