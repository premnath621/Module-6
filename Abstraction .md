# Abstract class example

from abc import ABC, abstractmethod

# Abstract class
class Shape(ABC):
    
    @abstractmethod
    def calculate_area(self):
        pass

# Rectangle subclass
class Rectangle(Shape):
    def __init__(self, length=5, breadth=3):
        self.length = length
        self.breadth = breadth

    def calculate_area(self):
        return self.length * self.breadth

# Circle subclass
class Circle(Shape):
    def __init__(self, radius=4):
        self.radius = radius

    def calculate_area(self):
        return 3.14 * self.radius * self.radius

# Create objects
rect = Rectangle()
circ = Circle()

# Output
print("Rectangle Area:", rect.calculate_area())
print("Circle Area:", circ.calculate_area())
