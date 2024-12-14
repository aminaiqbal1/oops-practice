# Python-practice
A collection of exercises and examples to practice Object-Oriented Programming (OOP) concepts in Python. Ideal for beginners to learn and master classes, objects, inheritance, polymorphism, encapsulation, and more.

A **class** in programming is a blueprint for creating objects (specific instances of that class). It defines the properties (attributes) and behaviors (methods) that the objects created from the class will have.


An **object** is an instance of a class that contains specific data and can use the methods defined by the class.
It's like a tangible thing created using the blueprint (class).

# make class and pass variable 
class AgeClass:
      Age = 78
      
# make object for call class variable

ageobject = AgeClass()

print(ageobject.Age)

# Define a class for function named sumvalue 
class sumvalue:
    
    # Define a method named sumvalue within the class
    def sumvaluve(self):
        # Print the sum of 34 and 46
        print(34 + 46)

# Create an object of the class sumvalue
sumobj = sumvalue()

# Call the sumvaluve method using the sumobj object
sumobj.sumvaluve()



