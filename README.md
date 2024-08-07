class Math:: This line starts the definition of the Math class.
@classmethod: This decorator indicates that the following method is a class method, which means it receives the class itself as the first argument instead of an instance of the class.
def add(cls, num1, num2):: Defines a class method add that takes two numbers as arguments and returns their sum. The cls parameter represents the class itself and is a convention in class methods.
def subtract(cls, num1, num2):: Similar to add, this is a class method that returns the difference between two numbers.
@staticmethod: This decorator indicates that the following method is a static method, which means it does not receive an implicit first argument (neither an instance nor a class).
def multiply(num1, num2):: Defines a static method multiply that takes two numbers and returns their product.
The print statements at the end of the program call these methods and print the results of addition, subtraction, and multiplication of the numbers 5 and 